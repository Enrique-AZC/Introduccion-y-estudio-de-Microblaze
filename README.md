# Introduccion-y-estudio-de-prestaciones-de-Microblaze
Conforma el trabajo final de la asignatura Sistemas Electrónicos Integrados (MUIT UGR)


Este proyecto tiene como objetivo estudiar las prestaciones de un **Microblaze**, procesador RISC de Xilinx, en tres aspectos clave utilizando las herramientas **Vivado** y **Vitis**:
1. **Área** (recursos utilizados).
2. **Rendimiento** (prueba de rendimiento en Vitis).
3. **Frecuencia máxima** (mediante el estudio de rutas críticas en Vivado).
4. **Consumo energético**.

El estudio se realiza configurando el **Microblaze** con tres presets diferentes: **área**, **rendimiento** y **frecuencia**, cada uno enfocado en optimizar una de las características mencionadas.

## Requisitos

- **Vivado**: Para sintetizar el diseño y obtener las métricas de **frecuencia máxima**, **área** y **consumo energético**.
- **Vitis**: Para realizar pruebas de rendimiento sobre el procesador Microblaze.

## Instalación

### 1. Clonación del repositorio

```bash
git clone https://github.com/Enrique-AZC/Introduccion-y-estudio-de-Microblaze
cd proyecto-microblaze

