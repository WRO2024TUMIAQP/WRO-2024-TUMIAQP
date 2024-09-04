# TUMI-AQP WRO 2024

### TUMI-AQP Repository for WRO 2024 Future Engineers

![TEAM TUMI](/T-PHOTOS/Formal-photo.jpg)

# 1. 🤖 Equipo WRO 2024 - Futuros Ingenieros

¡Bienvenidos al repositorio del equipo **Futuros Ingenieros** de la **WRO 2024** representando a **Arequipa, Perú**! 🇵🇪

## 1.1 🌟 Sobre Nosotros

| **Nombre**                        | **Rol**                                      | **Descripción**                                                               |
|-----------------------------------|----------------------------------------------|--------------------------------------------------------------------------------|
| **Joshua Huillca Fuentes**        | **Estratega y Analista Técnico**             | **El cerebro estratégico que siempre encuentra la mejor solución.**            |
| **Lucy Pérez Casazola**           | **Creativa y Diseñadora Técnica**            | **La mente creativa que da vida a nuestros diseños innovadores.**              |
| **Gabriel Palomino Mendoza**      | **Electrónica, Programación y Optimización** | **Especialista en electrónica y optimización de sistemas complejos.**          |
| **Cristian Villca Balcón**        | **Mentor**                                   | **Experto en robótica que nos guía con su vasta experiencia.**                 |
| **Bruno Layme Carpio**            | **Mentor**                                   | **Especialista en sistemas y automatización que refuerza nuestras habilidades.**|

## 1.2 🚀 Nuestro Objetivo

Trabajamos en equipo para lograr grandes cosas, con la meta de alcanzar el éxito en la **WRO 2024**. ¡Vamos con todo!

---
> [!NOTE]
> Este repositorio contiene toda la información relacionada con nuestro proyecto en la WRO 2024, incluyendo códigos, diseños y documentación técnica.

## Índice

1. [🤖 Equipo WRO 2024](#1-🤖EquipoWRO2024-FuturosIngenieros)
   - 1.1. [Componentes](#11-componentes)
   - 1.1.2. [Modelos](#12-modelos)
   - 1.1.3. [Electrónica](#13-electrónica)
   - 1.1.4. [Mecanismo de Ackerman](#14-mecanismo-de-ackerman)

2. [Software](#2-software)
   - 2.1. [Sensores](#21-sensores)
   - 2.2. [Posicionamiento y Estrategia](#22-posicionamiento-y-estrategia)

## 2.🛠️ Hardware

En esta sección, describimos los materiales clave utilizados en la construcción de nuestro coche autónomo. Cada material fue cuidadosamente seleccionado para asegurar la máxima precisión y fiabilidad durante la competencia.

## 2.1. 🔧 Componentes

- **2 x N20 Motors (800RPM):**  
  Estos motores compactos y potentes proporcionan la fuerza de conducción necesaria para el movimiento del coche, asegurando una excelente maniobrabilidad en la pista de competencia.

- **1 x MG995 Servo Motor:**  
  Utilizado para controlar el sistema de dirección, este servo motor permite giros precisos, siguiendo el principio de dirección de Ackerman.

### 2.1.2. ⚡ Fuente de Poder

- **1 x 11.1V 1500mAh Battery:**  
  Alimenta todos los componentes electrónicos, asegurando operación continua durante las pruebas y desafíos.

- **1 x LM2596 DC-DC Voltage Converter:**  
  Ajusta el voltaje de la batería para alimentar correctamente los diferentes componentes del sistema.

### 2.1.3. 🧠 Microcontroladores y Comunicación

- **1 x ESP32:**  
  El cerebro del coche autónomo, este microcontrolador maneja la lógica de control y la comunicación con los sensores y actuadores.

- **1 x ESP32-CAM con Módulo Flash:**  
  Añade capacidades de visión al coche, permitiendo la captura de imágenes y videos, útil para sistemas de visión artificial durante la competencia.

### 2.1.4. 🧱 Materiales de Construcción

- **800g de Filamento PLA:**  
  Utilizado en la impresión 3D de la estructura del coche, proporcionando un chasis ligero pero fuerte.

- **1 x PCB de Cobre de 10x15cm:**  
  Diseñada a medida para conectar eficientemente todos los componentes electrónicos, reduciendo la posibilidad de errores de cableado.

### 2.1.5. 🔌 Conectores y Cables

- **1 x Paquete de Cables Dupont Hembra y Macho:**  
  Utilizados para interconectar los componentes electrónicos, asegurando conexiones firmes y seguras.

- **1 x Paquete de Cables Jumper de 15cm (Hembra-Hembra, Macho-Macho, Hembra-Macho):**  
  Proporcionan flexibilidad en la configuración del circuito.

- **1 x Paquete de Tornillos M3 (100 piezas, Hembra y Macho):**  
  Utilizados para asegurar todas las piezas y componentes en su lugar.

### 2.1.6. 🛠️ Herramientas y Adhesivos

- **1 x Kit de Soldadura (Soldador de 30W, Estaño):**  
  Esencial para realizar conexiones permanentes y asegurar la integridad del circuito.

- **2 x Tubos de Pegamento (Triz) y 1 x 100g de Bicarbonato de Sodio:**  
  Utilizados para asegurar piezas pequeñas y realizar reparaciones rápidas.

### 2.1.7. 💡 Otros Componentes Electrónicos

- **1 x Driver H-Bridge TB6612FNG:**  
  Controla la dirección y velocidad de los motores, permitiendo un manejo preciso del coche.

- **1 x Interruptor Deslizante de Dos Posiciones:**  
  Utilizado para encender y apagar el sistema de manera segura.

### 2.1.8. ELECTRÓNICA

El sistema electrónico fue cuidadosamente diseñado para integrar todos los sensores y actuadores con la unidad central de procesamiento. Usamos una PCB personalizada para simplificar las conexiones y reducir las posibilidades de errores de cableado, lo que podría llevar a fallos en el sistema.

![First Part of Components](V-PHOTOS/COMPONENTS/FIRST_PART_OF_COMPONENTS.png)
![Second Part of Components](V-PHOTOS/COMPONENTS/SECOND_PART_OF_COMPONENTS.png)

### 3. Modelos

Desarrollamos modelos 3D del coche para simular su comportamiento y rendimiento bajo diversas condiciones. Estos modelos ayudaron a afinar el diseño antes de la producción real, ahorrando tanto tiempo como recursos.

En esta sección, puedes explorar una variedad de modelos 3D personalizados y piezas impresas en 3D creadas para nuestro proyecto. Cada modelo ha sido elaborado con atención al detalle, asegurando la compatibilidad con los estándares de la competencia.

![During printing](V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/ROBOT-3D/MODELS-3D/IMPRESION-3D.png)

> [!TIP]
> Puedes encontrar los archivos de diseño para las piezas impresas en 3D en la carpeta [/V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/MODELS-3D](./V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/MODELS-3D) del repositorio.

#### 3. PLACA PCB  
![PLACA PCB](V-PHOTOS/SECOND-PROTOTYPE/OTHER-PHOTOS/PCB/PLACA_PCB.png)

Diseñamos una placa PCB para consolidar todos los componentes electrónicos del robot autónomo en una estructura compacta y ordenada, minimizando errores de conexión y mejorando la eficiencia del sistema. Esta placa nos permite integrar de manera efectiva el ESP32, que procesa la información de los sensores y controla los actuadores. Los 7 sensores TOF VL53L0X miden distancias con precisión, y el sensor de color TCS3200 detecta señales visuales en la pista. Además, el giroscopio MPU6050 garantiza la estabilidad del robot, mientras que la ESP32 CAM captura imágenes del entorno. El servomotor MG995, controlado por el driver H-Bridge TB6612FNG.

### 1.10. Mecanismo de Ackerman

Implementamos el principio de dirección de Ackerman para asegurar que las ruedas del coche sigan la trayectoria correcta durante los giros, minimizando el desgaste de los neumáticos y mejorando el manejo general. Este mecanismo fue ajustado para trabajar sin problemas con nuestros algoritmos de control.

## 2. Software

El aspecto del software en el proyecto es fundamental para la capacidad del coche de navegar de forma autónoma. Nuestro stack de software incluye módulos para el procesamiento de datos de sensores, toma de decisiones y actuación, todos ejecutándose en un sistema operativo en tiempo real para asegurar un rendimiento rápido y confiable.

### 2.1. Sensores

Utilizamos una variedad de sensores que son fundamentales para el correcto funcionamiento del coche autónomo en la competencia:

- **7 Sensores TOF VL53LOX:**  
  Utilizados para la detección precisa de obstáculos, estos sensores ayudan a que el coche pueda evitar colisiones y navegar a través de entornos complejos.

- **1 Sensor de Color TCS3200:**  
  Empleado para detectar señales de color en la pista, crucial para la interpretación de marcadores de ruta o zonas específicas.

- **1 Giroscopio MPU6050:**  
  Proporciona información vital sobre la orientación y estabilidad del vehículo, permitiendo ajustes precisos durante la navegación.

### 2.2. Posicionamiento y Estrategia

El posicionamiento preciso es fundamental para que el coche autónomo pueda cumplir con las exigencias de la competencia. Para lograrlo, combinamos los siguientes

