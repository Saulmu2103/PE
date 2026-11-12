# **CONTROL DE SALAS TÉCNICAS**

## **INTRODUCCIÓN**

El objetivo es diseñar y construir un dispositivo de monitorización ambiental para salas técnicas que alojen *racks* y servidores. El equipo medirá temperatura, humedad y CO₂, enviará los datos a *Sentilo* para su procesamiento y activará acciones preventivas (alertas, ventilación, corte de alimentación o señalización) para reducir el desgaste prematuro de componentes y detectar/actuar ante riesgos de incendio.

## **MATERIALES Y TAREAS**

### Componentes

ESP32-S3

Sensor de humedad

Sensor de temperatura

Sensor de CO₂

## Tareas



- **Montaje: Saül**

Descripción: montaje físico de la placa y los sensores.

- **Programación de ESP-32: Sebastian**

Descripción: *firmware* en ESP32-S3 que lee sensores, gestiona umbrales y envía telemetría por *Wi‑Fi* a *Sentilo*.

- **Programación de *Sentilo*: Pere**

Descripción: creación de sensores/actuadores en Sentilo, ingestión de datos vía API/HTTP, normalización y reglas de procesamiento.