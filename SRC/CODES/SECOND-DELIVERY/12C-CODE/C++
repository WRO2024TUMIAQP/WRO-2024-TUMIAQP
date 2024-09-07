#include <Wire.h>
#include <Adafruit_VL53L0X.h>

// Definir direcciones I2C para los 7 sensores
#define SENSOR_ADDRESSES {0x30, 0x31, 0x32, 0x33, 0x34, 0x35, 0x36}

// Definir los pines XSHUT para cada sensor
#define XSHUT_PINS {15, 2, 4, 16, 17, 5, 18}

// Crear objetos para los sensores VL53L0X
Adafruit_VL53L0X lox[7];

// Pines XSHUT
int xshut_pins[] = XSHUT_PINS;
int sensor_addresses[] = SENSOR_ADDRESSES;

// Esta variable almacena las mediciones
VL53L0X_RangingMeasurementData_t measurements[7];

// Inicializar los sensores
void setID() {
  // Poner todos los sensores en modo de reset
  for (int i = 0; i < 7; i++) {
    pinMode(xshut_pins[i], OUTPUT);
    digitalWrite(xshut_pins[i], LOW);
  }
  delay(10);

  // Sacar todos los sensores del modo de reset y configurar sus direcciones
  for (int i = 0; i < 7; i++) {
    digitalWrite(xshut_pins[i], HIGH);
    delay(10);
    
    if (!lox[i].begin(sensor_addresses[i])) {
      Serial.print("Error al iniciar el sensor ");
      Serial.println(i);
    } else {
      Serial.print("Sensor ");
      Serial.println(i);
    }
    
    // No apagues el sensor actual hasta que todos estén inicializados
  }
}

void read_sensors() {
  for (int i = 0; i < 7; i++) {
    lox[i].rangingTest(&measurements[i], false); // Obtener la medición

    Serial.print("Sensor ");
    Serial.print(i);
    Serial.print(": ");
    if (measurements[i].RangeStatus != 4) {  // Si no hay error
      Serial.print(measurements[i].RangeMilliMeter);
      Serial.print(" mm");
    } else {
      Serial.print("Error de medición");
    }
    Serial.println();
  }
}

void setup() {
  Serial.begin(115200);

  // Esperar hasta que el puerto serial esté abierto
  while (!Serial) { delay(1); }

  Serial.println("Configurando sensores...");
  setID();
  Serial.println("Sensores iniciados.");
}

void loop() {
  read_sensors();
  delay(200);  // Espera medio segundo antes de la siguiente lectura
}
