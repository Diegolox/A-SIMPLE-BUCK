# Mini Adjustable Buck Converter Module
> A small adjustable DC-DC buck converter module designed as a first step into power supply design.

## 🇬🇧 Project Description

This project is about designing a small **adjustable buck converter module**.

Until now, I have usually used ready-made DC-DC modules in my projects. However, for future PCBs I would like to design my own power supplies instead of depending on external modules. Since I am not yet fully familiar with switching regulator design, I thought the most logical first step was to build a simple standalone module, test it, and understand what can go wrong before integrating this kind of circuit into larger boards.

<img align="center" alt="Mini Adjustable Buck Converter Module 3D render" width="1200" src="./assets/img/3D.png" />

The design is based on the **AP63200WU-7**, an adjustable synchronous buck converter from Diodes Incorporated. The PCB was designed in **KiCad** as a 2-layer board, with GND planes on both layers, stitching vias, test points, and a compact layout around the regulator.

## Features

- Adjustable buck converter module
- Based on the AP63200WU-7
- Input range of the IC: 3.8 V to 32 V
- Output mainly intended around 5 V
- 10 µH SMD power inductor
- Bourns 3296W trimmer for output adjustment
- Test points for easier measurements
- 2-layer PCB designed for JLCPCB

### LAYOUT
<img align="center" alt="PCB layout" width="1200" src="./assets/img/LAYOUT.png" />

### SCHEMATIC
<img align="center" alt="PCB layout" width="1200" src="./assets/img/SCH.svg" />

This is a first version focused on learning and testing. The next steps are to manufacture the PCB, assemble it, and measure ripple, temperature and regulation under load.

---

# Módulo buck ajustable compacto

## 🇪🇸 Descripción del proyecto

Este proyecto consiste en diseñar un pequeño **módulo buck converter ajustable**.

Hasta ahora, en muchos proyectos he usado módulos DC-DC comerciales ya hechos. Sin embargo, para futuras PCBs me gustaría poder diseñar mis propias fuentes de alimentación en lugar de depender siempre de módulos externos. Como todavía no estoy muy familiarizado con el diseño de fuentes conmutadas, he visto más lógico empezar con un módulo sencillo, probarlo por separado y entender qué cosas pueden fallar antes de integrarlo directamente en placas más grandes.

<img align="center" alt="Mini Adjustable Buck Converter Module 3D render" width="1200" src="./assets/img/3D.png" />

El diseño está basado en el **AP63200WU-7**, un convertidor buck síncrono ajustable de Diodes Incorporated. La PCB está diseñada en **KiCad** como una placa de 2 capas, con planos de masa en ambas caras, vías de stitching, test points y un layout compacto alrededor del regulador.

## Características

- Módulo buck converter ajustable
- Basado en el AP63200WU-7
- Rango de entrada del chip: 3.8 V a 32 V
- Salida pensada principalmente alrededor de 5 V
- Bobina SMD de potencia de 10 µH
- Trimmer Bourns 3296W para ajustar la salida
- Test points para facilitar medidas
- PCB de 2 capas pensada para JLCPCB

### LAYOUT
<img align="center" alt="PCB layout" width="1200" src="./assets/img/LAYOUT.png" />

### SCHEMATIC
<img align="center" alt="PCB layout" width="1200" src="./assets/img/SCH.svg" />

Esta es una primera versión orientada a aprendizaje y pruebas. Los próximos pasos son fabricar la PCB, montarla y medir ripple, temperatura y regulación bajo carga.
