 Análisis de Señales y Sistemas de Conversión Digital-Analógico

Descripción:
Este proyecto contiene una serie de herramientas y funciones para analizar y visualizar diferentes tipos de señales, tanto en tiempo continuo como discreto. Además, incluye una sección dedicada al análisis de sistemas de conversión digital-analógico (DAC).

Requisitos:
- Python 3.x
- NumPy
- Matplotlib
- SciPy

Uso:
El proyecto se divide en cuatro tareas principales:

1. Tarea 1: Análisis de señales senoidales, exponenciales, triangulares y cuadradas en tiempo continuo y discreto.
- Uso: python main.py tarea_1 <señal> (donde <señal> puede ser seno, exponencial, triangular o cuadrada)
2. Tarea 2: Análisis de la frecuencia de una señal senoidal.
- Uso: python main.py tarea_2 <frecuencia> (donde <frecuencia> es la frecuencia deseada)
3. Tarea 3: Comparación de señales senoidales con diferentes amplitudes, frecuencias y fases.
- Uso: python main.py tarea_3 <amplitud> <frecuencia> <fase> (donde <amplitud>, <frecuencia> y <fase> son los parámetros deseados)
4. Tarea 4: Análisis de la resolución de un sistema de conversión digital-analógico (DAC).
- Uso: python main.py tarea_4 <bits> (donde <bits> es el número de bits del DAC)

Funciones:
El proyecto incluye varias funciones para graficar y analizar señales, incluyendo:

- continuous_plotter: Grafica una señal en tiempo continuo.
- discrete_plotter: Grafica una señal en tiempo discreto.
- dac_plotter: Grafica la salida de un DAC.

Ejemplos:
- python main.py tarea_1 seno
- python main.py tarea_2 2
- python main.py tarea_3 1 2 0.785
- python main.py tarea_4 8
