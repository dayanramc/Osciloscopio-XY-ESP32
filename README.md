# Osciloscopio-XY-ESP32
# Osciloscopio XY con ESP32

## Descripción

Este proyecto consiste en la implementación de un sistema capaz de dibujar figuras en un osciloscopio utilizando el modo XY, mediante el uso de un microcontrolador ESP32.

El sistema genera señales analógicas en los ejes X y Y a partir de coordenadas previamente definidas, permitiendo visualizar trayectorias como figuras geométricas o paisajes.

---

## Tecnologías utilizadas

- ESP32  
- DAC interno (pines 25 y 26)  
- Arduino IDE  
- SimulIDE (simulación)  
- Osciloscopio  

---

## Funcionamiento

El ESP32 recorre una lista de coordenadas (X,Y) y las envía como señales analógicas al osciloscopio.

Esto permite controlar el movimiento del haz electrónico y dibujar figuras en pantalla.

---

## Simulación

Se utilizó Arduino UNO en SimulIDE para simular el comportamiento del sistema, debido a la falta de soporte para ESP32 y DAC en dicho entorno.

---

## Autor

- Dayan Ramirez Cruz
