# TUMI-AQP WRO 2024

### TUMI-AQP Repository for WRO 2024 Future Engineers

![TEAM TUMI](/T-PHOTOS/Formal-photo.jpg)

# 🤖 Equipo WRO 2024 - Futuros Ingenieros

¡Bienvenidos al repositorio del equipo **Futuros Ingenieros** de la **WRO 2024** representando a **Arequipa, Perú**! 🇵🇪

## 🌟 Sobre Nosotros

| **Nombre**                        | **Rol**                                      | **Descripción**                                                               |
|-----------------------------------|----------------------------------------------|--------------------------------------------------------------------------------|
| **Joshua Huillca Fuentes**        | **Estratega y Analista Técnico**             | **El cerebro estratégico que siempre encuentra la mejor solución.**            |
| **Lucy Pérez Casazola**           | **Creativa y Diseñadora Técnica**            | **La mente creativa que da vida a nuestros diseños innovadores.**              |
| **Gabriel Palomino Mendoza**      | **Electrónica, Programación y Optimización** | **Especialista en electrónica y optimización de sistemas complejos.**          |
| **Cristian Villca Balcón**        | **Mentor**                                   | **Experto en robótica que nos guía con su vasta experiencia.**                 |
| **Bruno Layme Carpio**           | **Mentor**                                   | **Especialista en sistemas y automatización que refuerza nuestras habilidades.**|

## 🚀 Nuestro Objetivo

Trabajamos en equipo para lograr grandes cosas, con la meta de alcanzar el éxito en la **WRO 2024**. ¡Vamos con todo!

---
> [!NOTE]
> Este repositorio contiene toda la información relacionada con nuestro proyecto en la WRO 2024, incluyendo códigos, diseños y documentación técnica


## Contents

- [Hardware](#hardware)
  - [Components](#components)
  - [Models](#models)
  - [Electronics](#electronics)
  - [Ackerman's](#ackermans)
- [Software](#software)
  - [Sensors](#sensors)
  - [Position and Strategy](#position_and_strategy)
## 🛠️ Materials Used

In this section, we outline the key materials used in the construction of our autonomous car. Each material was carefully selected to ensure the highest level of precision and reliability during the competition.

### 🔧 Motors and Actuators
- **2 x N20 Motors (800RPM):**  
  These compact and powerful motors provide the necessary driving force for the car's movement, ensuring excellent maneuverability on the competition track.
  
- **1 x MG995 Servo Motor:**  
  Used to control the steering system, this servo motor enables precise turns, following the Ackerman steering principle.

### ⚡ Power Supply
- **1 x 11.1V 1500mAh Battery:**  
  Powers all the electronic components, ensuring continuous operation during tests and challenges.
  
- **1 x LM2596 DC-DC Voltage Converter:**  
  Adjusts the battery voltage to properly power the different system components.

### 🧠 Microcontrollers and Communication
- **1 x ESP32:**  
  The brain of the autonomous car, this microcontroller handles control logic and communication with sensors and actuators.
  
- **1 x ESP32-CAM with Flash Module:**  
  Adds vision capabilities to the car, allowing for image and video capture, which can be useful for artificial vision systems during the competition.

### 🧱 Construction Materials
- **800g of PLA Filament:**  
  Used in the 3D printing of the car's structure, providing a lightweight yet strong chassis.
  
- **1 x 10x15cm Copper PCB Board:**  
  Custom-designed to efficiently connect all electronic components, reducing the possibility of wiring errors.

### 🔌 Connectors and Wires
- **1 x Pack of Female and Male Dupont Wires:**  
  Used to interconnect electronic components, ensuring firm and secure connections.
  
- **1 x Pack of 15cm Jumper Wires (Female-Female, Male-Male, Female-Male):**  
  Provides flexibility in circuit configuration.
  
- **1 x Pack of M3 Screws (100 pieces, Female and Male):**  
  Used to securely fasten all parts and components in place.

### 🛠️ Tools and Adhesives
- **1 x Soldering Kit (30W Soldering Iron, Tin):**  
  Essential for making permanent connections and ensuring circuit integrity.
  
- **2 x Glue Tubes (Triz) and 1 x 100g Baking Soda:**  
  Used to secure small parts and make quick repairs.

### 💡 Other Electronic Components
- **1 x TB6612FNG H-Bridge Driver:**  
  Controls motor direction and speed, allowing precise car handling.
  
- **1 x Two-Position Slide Switch:**  
  Used to safely turn the system on and off.


### Models

Desarrollamos modelos 3D del coche para simular su comportamiento y rendimiento bajo diversas condiciones. Estos modelos ayudaron a afinar el diseño antes de la producción real, ahorrando tanto tiempo como recursos.

En esta sección, puedes explorar una variedad de modelos 3D personalizados y piezas impresas en 3D creadas para nuestro proyecto. Cada modelo ha sido elaborado con atención al detalle, asegurando la compatibilidad con los estándares de la competencia.

![During printing](V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/ROBOT-3D/MODELS-3D/IMPRESION-3D.png)

Puedes encontrar los archivos de diseño para las piezas impresas en 3D en la carpeta [/V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/MODELS-3D](./V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/MODELS-3D) del repositorio.

### ELECTRONICS

El sistema electrónico fue cuidadosamente diseñado para integrar todos los sensores y actuadores con la unidad central de procesamiento. Usamos una PCB personalizada para simplificar las conexiones y reducir las posibilidades de errores de cableado, lo que podría llevar a fallos en el sistema.

![First Part of Components](V-PHOTOS/COMPONENTS/FIRST_PART_OF_COMPONENTS.png)
![Second Part of Components](V-PHOTOS/COMPONENTS/SECOND_PART_OF_COMPONENTS.png)

#### PLACA PCB  
![PLACA PCB](V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/PCB/PLACA_PCB.png)

Diseñamos una placa PCB para consolidar todos los componentes electrónicos del robot autónomo en una estructura compacta y ordenada, minimizando errores de conexión y mejorando la eficiencia del sistema. Esta placa nos permite integrar de manera efectiva el ESP32, que procesa la información de los sensores y controla los actuadores. Los 7 sensores TOF VL53L0X miden distancias con precisión, y el sensor de color TCS3200 detecta señales visuales en la pista. Además, el giroscopio MPU6050 garantiza la estabilidad del robot, mientras que la ESP32 CAM captura imágenes del entorno. El servomotor MG995, controlado por el driver H-Bridge TB6612FNG.

### Ackerman's

Implementamos el principio de dirección de Ackerman para asegurar que las ruedas del coche sigan la trayectoria correcta durante los giros, minimizando el desgaste de los neumáticos y mejorando el manejo general. Este mecanismo fue ajustado para trabajar sin problemas con nuestros algoritmos de control.

## Software

El aspecto del software en el proyecto es fundamental para la capacidad del coche de navegar de forma autónoma. Nuestro stack de software incluye módulos para el procesamiento de datos de sensores, toma de decisiones y actuación, todos ejecutándose en un sistema operativo en tiempo real para asegurar un rendimiento rápido y confiable.

### Sensors

Utilizamos una variedad de sensores que son fundamentales para el correcto funcionamiento del coche autónomo en la competencia:

- **7 Sensores TOF VL53LOX:** Utilizados para la detección precisa de obstáculos, estos sensores ayudan a que el coche pueda evitar colisiones y navegar a través de entornos complejos.
- **1 Sensor de Color TCS3200:** Empleado para detectar señales de color en la pista, crucial para la interpretación de marcadores de ruta o zonas específicas.
- **1 Giroscopio MPU 6050:** Proporciona información vital sobre la orientación y estabilidad del vehículo, permitiendo ajustes precisos durante la navegación.

### Position and Strategy

El posicionamiento preciso es fundamental para que el coche autónomo pueda cumplir con las exigencias de la competencia. Para lograrlo, combinamos los siguientes componentes:

- **7 Sensores TOF VL53LOX:** Los sensores TOF están posicionados estratégicamente alrededor del coche para medir la distancia a las paredes y mantener una dirección recta. Cuando uno de los sensores TOF frontales (dependiendo de la dirección inicial tomada al comenzar la ronda) detecta el final de una esquina en el centro de la pista, el sistema de dirección Ackerman se activa. Esto ajusta la dirección del coche hasta que los sensores TOF estén alineados con las distancias predefinidas, garantizando así una navegación precisa y una trayectoria correcta en la pista.
- **SENSOR DE COLOR -TCS3200:** Al detectar uno de los colores de las líneas de la pista (azul o anaranjado) asignados, se activa el sensor TOF correspondiente para iniciar el giro, lo que determina la trayectoria del robot, ya sea en sentido horario o antihorario. Este mecanismo permite al robot adaptarse a las señales visuales de la pista.

