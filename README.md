# 🌬️ Proyecto Final: Análisis y Pronóstico de Series de Tiempo (ESCOM IPN)

Repositorio oficial para el proyecto final de la materia de Análisis de Series de Tiempo. En este repositorio aplicaremos un flujo completo de ciencia de datos sobre datos reales de un aerogenerador (turbina eólica) para predecir su comportamiento futuro.

## 👥 Equipo y Responsabilidades
* **Asignación de la Fase 1 (Definición y Horizonte):** @~Pinedah 

---

## 🛠️ Estructura del Repositorio
```text
├── data/
│   ├── dataset_original.csv      # Datos SCADA crudos
│   └── README.txt                # Ficha técnica de variables
├── notebooks/
│   ├── 01_exploracion_y_definicion.ipynb  # Script de exploración inicial
└── README.md

```

### 🚀 Siguientes Pasos para el Equipo (Fase 1)

Para cumplir con los requisitos iniciales del proyecto[cite: 1], sigan estos pasos secuenciales:

1. **Ejecutar el script de exploración:**
   Corran el notebook `01_exploracion_y_definicion.ipynb` para inspeccionar las columnas y la estructura temporal del dataset.
2. **Descubrir y Definir la Variable Objetivo y Frecuencia:**
   Analicen las variables meteorológicas y operativas. Deben descubrir en equipo cuál es la columna que mide la generación real de energía y decidir el remuestreo de la frecuencia (ej. horaria)[cite: 1].
3. **Establecer el Horizonte de Pronóstico:**
   Acuerden cuántos pasos hacia adelante pronosticaremos en el modelo (ej. predecir las próximas 48 o 72 horas)[cite: 1].
