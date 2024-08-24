# TUMI-AQP WRO 2024

### TUMI-AQP Repository for WRO 2024 Future Engineers

![TEAM TUMI](/T-PHOTOS/Formal-photo.jpg)

## Contents

- [Hardware](#hardware)
  - [Components](#components)
  - [Models](#models)
  - [Electronics](#electronics)
  - [Ackerman's](#ackermans)
- [Software](#software)
  - [Sensors](#sensors)
  - [Position](#position)
  - [Strategy](#strategy)
- [Photos](#photos)
  - [Car images](#car-images)
  - [Team images](#team-images)
- [Videos](#videos)
  - [Demonstration videos](#demonstration-videos)
- [Legal](#legal)
  - [License](#license)
  - [Credits](#credits)

## Hardware

Building an autonomous car for this challenge involves a meticulous process of reimagining and redesigning various components to achieve precision, safety, and efficiency. In this project, we focused on enhancing the car’s steering mechanism, designing a custom-printed circuit board (PCB) to connect all the components seamlessly, and optimizing the overall mechanical structure for better performance.

### Components

In this section, we detail the key components used in the construction of the car, including sensors, actuators, and controllers. Each component was selected to ensure the highest level of accuracy and reliability in autonomous driving.
-2 Placa de desarrrollo
-2 Motoreductor
-3 Motor N20 800RPM
-8 Sensores TOF VL53LOX
-2 Batería tipo 11.1V 1500mAh
-2 Giroscopio MPU 6050
-2kg Filamento PLA
-1 ESP 32
-1 ESP 32 CAM y modulo de carga de codigo
-4 Neumaticos arduino
-2 Pegamentos (triz)
-1 Bicarbonato de sodio 100 gr
-1 Kit de soldadura (Cautin 30W, estaño)
-2 Placa PCB de cobre (10^15)
-3 Driver puente H (TB6612FNG)
-1 Conversor de voltaje dc-dc lm2596
-1 Paquete espadines hembra y macho
-1 Cargador IMAX B3 PRO
-1 Paquete de Jumpers (Hembra-Macho,h-h y m-m)15cm
-1 Pack tornillos m3 (100u hembras y macho)
-1 Cable 2m ethernet cat 8 
-2 Interruptor de dos posiciones deslizantes 
-3 servomotores mg90s
-2 TCS3200 color sensor interfacing with ESP32
### Models

We developed 3D models of the car to simulate its behavior and performance under various conditions. These models helped in fine-tuning the design before actual production, saving both time and resources.

### Electronics

The electronics system was carefully designed to integrate all sensors and actuators with the central processing unit. We used a custom PCB to streamline connections and reduce the chances of wiring errors, which could lead to system failures.

### Ackerman's

We implemented the Ackerman steering principle to ensure that the car's wheels follow the correct path during turns, minimizing tire wear and improving overall handling. This mechanism was fine-tuned to work seamlessly with our control algorithms.

## Software

The software aspect of the project is critical to the car’s ability to navigate autonomously. Our software stack includes modules for sensor data processing, decision-making, and actuation, all running on a real-time operating system to ensure quick and reliable performance.

### Sensors

We employed a variety of sensors, including LiDAR, cameras, and ultrasonic sensors, to gather environmental data. This information is processed in real-time to detect obstacles, determine position, and plan the car's path.

### Position

Accurate positioning is crucial for the car's navigation. We combined GPS data with sensor input to determine the car's exact location, allowing it to navigate complex environments with high precision.

### Strategy

The strategy module is responsible for making high-level decisions, such as path planning and obstacle avoidance. It uses advanced algorithms to calculate the most efficient and safest route to the destination.

## Photos

### Car images

Here are some images of the car at various stages of development and testing, showcasing the design and functionality of the autonomous system.

### Team images

Meet the team behind the TUMI-AQP WRO 2024 project. These images capture the hard work and dedication of our team members as they bring the project to life.

## Videos

### Demonstration videos

Watch our demonstration videos to see the car in action. These videos highlight the car's autonomous capabilities, including obstacle avoidance, path following, and more.

## Legal

### License

This project is licensed under the MIT License, allowing for open-source collaboration and development. Feel free to use and modify our code and designs, but please give credit to the original authors.

### Credits

This project was made possible through the efforts of the TUMI-AQP team, with support from our mentors, sponsors, and the broader community. Special thanks to everyone who contributed to the success of this project.
