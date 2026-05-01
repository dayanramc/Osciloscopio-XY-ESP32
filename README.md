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
## Conclusiones

Se logró implementar un sistema capaz de generar figuras en un osciloscopio en modo XY mediante el uso del ESP32, aprovechando sus salidas DAC para producir señales analógicas en los ejes X y Y.

El uso de coordenadas permitió controlar con precisión la trayectoria del haz, demostrando la relación entre señales eléctricas y representación gráfica.

Se evidenció que la velocidad de actualización de los puntos influye directamente en la calidad de la imagen, siendo necesario ajustar los tiempos para obtener una visualización estable.

La simulación con Arduino UNO permitió validar el comportamiento general del sistema, aunque presentó limitaciones debido al uso de PWM en lugar de señales analógicas reales.

Finalmente, la implementación en hardware real con ESP32 ofreció mejores resultados en estabilidad, precisión y calidad de la señal.
---

## Autor

- Dayan Ramirez Cruz
