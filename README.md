# intro_cd_202610
Repositorio de la clase de Introducción a la Ciencia de Datos 2026/03/26

# Proyecto de Ciencia de Datos aplicado al Fútbol
## Análisis de estadísticas de jugadores y equipos
### Descripción
Este proyecto busca aplicar conceptos fundamentales de la ciencia de datos mediante el análisis de información relacionada con el fútbol. A partir de un conjunto de datos que contiene estadísticas de jugadores y equipos (goles, asistencias, partidos jugados, entre otros), se exploran patrones, tendencias y conclusiones relevantes utilizando herramientas básicas de análisis de datos.

#### Objetivos principales
- Limpieza de datos
- Análisis exploratorio (EDA)
- Visualización de información
- Interpretación de resultados para la toma de decisiones

##### Tecnologías utilizadas
- Python 3.10
- Pandas
- Matplotlib

###### Nivel del proyecto
Introductorio, priorizando la comprensión de procesos sobre la complejidad técnica.

---

## Ejemplos visuales

Imagen simple  
![Celebración de gol](celebracion.jpg)

Imagen desde URL externa  
![Estadio lleno](https://upload.wikimedia.org/wikipedia/commons/3/3e/Signal_Iduna_Park_2019.jpg)

Imagen con enlace (clickeable)  
[![Balón en cancha](https://upload.wikimedia.org/wikipedia/commons/d/d3/Soccer_ball.svg)](https://www.fifa.com)

Imagen con tamaño personalizado  
<img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Soccer_field_-_empty.jpg" alt="Cancha de fútbol" width="400"/>

Imagen centrada  
<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/Football_training.jpg" alt="Entrenamiento de equipo" width="500"/>
</p>

Varias imágenes en fila  
<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Soccer_ball.svg" width="200"/>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Cristiano_Ronaldo_celebrating.jpg" width="200"/>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Signal_Iduna_Park_2019.jpg" width="200"/>
</p>

---

## Bloques de Código

Python  
```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv("estadisticas_futbol.csv")
print(df.head())
