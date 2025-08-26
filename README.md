![Logo Institucional](https://github.com/JonatanBogadoUNLZ/PPS-Jonatan-Bogado/blob/9952aac097aca83a1aadfc26679fc7ec57369d82/LOGO%20AZUL%20HORIZONTAL%20-%20fondo%20transparente.png)
# Universidad Nacional de Lomas de Zamora - Facultad de Ingeniería
TÍTULO DEL PROYECTO
Introducción / Objetivo

En la Universidad Nacional de Lomas de Zamora, nuestra Facultad de Ingeniería se dedica a la formación de profesionales en diversas ramas de la ingeniería. Este repositorio corresponde al proyecto de [tu área o especialidad], desarrollado como parte del curso de [nombre del curso] de la carrera de Ingeniería Mecatrónica.

El objetivo de este proyecto es diseñar y construir un robot de balanceo autónomo reutilizando la estructura y controladora de un hoverboard, reprogramada y controlada por una placa ESP32, incorporando un sistema de visión artificial y una aplicación móvil para control manual

Índice

Descripción

Instrucciones de Uso

Tecnologías Utilizadas

Listado de Componentes

Esquemáticos

Fotos / Videos

Autor

Descripción

Este proyecto se basa en la implementación de un robot de balanceo tipo self-balancing utilizando la base de un hoverboard, controlado por una placa ESP32 custom.
El sistema integra un sensor inercial MPU6050 para el control de estabilidad, motores brushless gestionados mediante la controladora original del hoverboard reprogramada, y un módulo de visión artificial basado en una cámara estéreo PS5 y Raspberry Pi 5.

Se complementa con:

Una aplicación móvil (Kotlin) para control manual del robot.

Un módulo en ROS 2 (Python + OpenCV) para navegación autónoma y procesamiento de visión.

Comunicación mediante sockets TCP entre los diferentes sistemas.

El enfoque del proyecto es explorar el control dinámico de robots de balanceo y su integración con sistemas de visión y navegación autónoma.

Instrucciones de Uso

Para utilizar este proyecto, sigue los pasos:

Paso 1. Clonar este repositorio general y los repositorios relacionados.

Paso 2. Montar el hardware de acuerdo a los planos en la carpeta PLANOS.

Paso 3. Cargar el firmware del ESP32 desde el repositorio Mainboard.

Paso 4. Instalar y ejecutar la aplicación móvil desde HoverRobotApp.

Paso 5. Ejecutar el stack de navegación en ROS 2 desde HoverRobotNavigation.

Paso 6. Realizar pruebas en entorno controlado y luego en entornos reales.


Tecnologías Utilizadas

Robótica / Control: ESP32, motores brushless, controladora de hoverboard.

Electrónica: MPU6050, cámara estéreo PS5, placa ESP32 custom.

Programación: C, Python, Kotlin.

Plataformas: ROS 2, OpenCV, Raspberry Pi 5.

Comunicación: Sockets TCP.

Visión / IA: Procesamiento de imágenes, navegación autónoma.

Listado de Componentes

Placa ESP32 custom – microcontrolador principal.

IMU MPU6050 – medición de aceleración y giroscopio para balanceo.

Motores brushless – tracción principal, controlados mediante la controladora original del hoverboard.

Cámara estéreo PS5 – captura del entorno para visión artificial.

Raspberry Pi 5 – procesamiento de visión y ejecución de ROS 2.

Esquemáticos

A continuación se presentan los esquemáticos y diagramas de diseño que explican cómo se ensamblan y operan los sistemas del proyecto:

- PENDIENTE - 

Fotos / Videos

- PENDIENTE -

[Enlaces a las imágenes o videos almacenados en la carpeta "MULTIMEDIA"]

Autor

Este proyecto fue realizado por Patricio Garcés como parte de la carrera de Ingeniería Mecatrónica en la Facultad de Ingeniería de la Universidad Nacional de Lomas de Zamora.



Repositorios relacionados

Mainboard (ESP32): HoverRobot-ESP32

Aplicación móvil (Kotlin): HoverRobotApp-balancing-robot

Navegación en ROS 2: HoverRobotNavigation