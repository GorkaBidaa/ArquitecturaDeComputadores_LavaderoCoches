# 🖥️ Arquitectura de Computadores - Proyecto: Microprocesador 80C552

[![Nota Final](https://img.shields.io/badge/Nota%20Final-9.1%20%2F%2010-brightgreen?style=for-the-badge)](https://img.shields.io/badge/Nota%20Final-9.1%20%2F%2010-brightgreen?style=for-the-badge)
[![Hardware](https://img.shields.io/badge/Microcontrolador-80C552%20(Core%208051)-blue?style=flat-square)](https://img.shields.io/badge/Microcontrolador-80C552%20(Core%208051)-blue?style=flat-square)
[![IDE](https://img.shields.io/badge/Entorno-Keil%20%C2%B5Vision-orange?style=flat-square)](https://img.shields.io/badge/Entorno-Keil%20%C2%B5Vision-orange?style=flat-square)

Este repositorio contiene el código fuente, la configuración y la documentación del proyecto final desarrollado para la asignatura **Arquitectura de Computadores**, cursada en la Escuela de Ingeniería Informática de Gestión y Sistemas de Información de San Mamés (UPV/EHU). 

Esta asignatura y su proyecto creo que son uno de los apartados más difíciles de la carrera, por eso dejo por aquí mi implementación del año 2025. El proyecto estuvo bien realizado y creo que puede ser útil para tenerlo en cuenta ya que sacamos un **9.1 / 10**.

## 🎯 Descripción del Proyecto

El objetivo de este software es el control automatizado y concurrente de un **lavadero de coches**. El sistema ha sido diseñado, programado a bajo nivel y simulado para el microcontrolador **Philips 80C552** utilizando el entorno **Keil µVision2**.

Para lograr el desarrollo del proyecto, el programa se basa en un **Generador de Eventos único** y una **Máquina de Estados**

## 🛠️ Especificaciones Técnicas

* **Arquitectura:** Microcontrolador Philips Semiconductors 80C552 (8-bit, derivado núcleo 8051).
* **Lenguaje de Programación:** Ensamblador puro (ASM 8051).
* **Entorno de Simulación e IDE:** Keil µVision2.

## 📂 Estructura del Repositorio


* `/src`: Código fuente y entorno del proyecto.
  * `Lavadero.Uv2`: Archivo principal del Workspace para abrir el proyecto en Keil µVision2.
  * `Lavadero.a`: Código fuente principal escrito íntegramente en lenguaje ensamblador (ASM 8051).
* `/documentacion`: Información técnica del desarrollo.
  * `PF_AC27698_2024-25_Gorka_Bidaguren_Eduardo_Rocha_Memoria.pdf`: Memoria técnica detallando el diseño del hardware, diagramas de estado, flujos lógicos y cálculos matemáticos para la configuración de los temporizadores.
