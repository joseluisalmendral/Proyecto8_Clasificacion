
# Predicción Abandono Empleados



## Descripción del Proyecto

El principal desafío de este proyecto es abordar una de las preguntas más importantes para cualquier departamento de Recursos Humanos: **¿qué empleados tienen más probabilidades de quedarse en la empresa y cuáles podrían decidir irse?**  
Para lograr esto, se ha desarrollado un modelo de machine learning capaz de predecir si un empleado permanecerá en la empresa o decidirá marcharse. El objetivo es proporcionar a las organizaciones una herramienta predictiva para retener talento y diseñar estrategias más efectivas en la gestión de personal.

## Instalación Entorno

Clonar repositorio y ejecutar el siguiente comando:

```bash
pip install -r requirements.txt
```

## Estructura Proyecto

```
Proyecto8-Prediccion_Abandono_Empleados/
├── datos/
│   ├── futuro_estudio/         # Datos para estudios futuros.
│   ├── tratados/               # Datos procesados.
│   ├── diccionario-datos.xlsx  # Diccionario de datos con información relevante.
│   ├── employee_survey_data.csv # Encuestas realizadas a los empleados.
│   ├── general_data.csv         # Información general de los empleados.
│   └── manager_survey_data.csv  # Encuestas realizadas a los managers.
│
├── notebooks/
│   ├── config.py               # Configuración general del proyecto.
│   ├── iteracion1/             # Iteración inicial de análisis y modelado.
│   │   ├── 1_exploracion_inicial.ipynb  # Exploración inicial de los datos.
│   │   ├── 2_EDA.ipynb                  # Análisis exploratorio de datos.
│   │   ├── 3_escalado_y_encoding.ipynb  # Escalado y codificación de variables.
│   │   ├── 4_predicciones.ipynb         # Predicciones del modelo.
│   │   └── detalles_iteracion.md        # Detalles sobre la iteración.
│
├── src/
│   ├── analisis_estadistico/   # Scripts para análisis estadísticos avanzados.
│   ├── clasificacion/          # Algoritmos y scripts de clasificación.
│   ├── combinatoria/           # Scripts para generación de combinatorias.
│   ├── eda/                    # Scripts relacionados con el EDA.
│   └── regresion/              # Scripts de regresión.
│
├── transformers/
│   └── base/
│       ├── one_hot_encoder.pkl  # Codificador One-Hot.
│       ├── robust_scaler.pkl    # Escalador robusto.
│       └── target_encoder.pkl   # Codificador de variables categóricas.
│
├── priv/                       # Archivos confidenciales o privados.
├── requirements.txt            # Dependencias del proyecto.
├── README.md                   # Documentación del proyecto.
└── .gitignore                  # Archivos y directorios ignorados por Git.

```

## Puntos a Remarcar

- Los datos utilizados en este proyecto provienen de diferentes encuestas y registros internos de la empresa, distribuidos en los archivos presentes en la carpeta `datos/`.
- El modelo de machine learning desarrollado será clave para ayudar a Recursos Humanos a anticipar decisiones importantes relacionadas con el personal.

## Conclusiones

Las conclusiones específicas del análisis y modelado se encuentran detalladas en el archivo `notebooks/iteracion1/4_predicciones.ipynb`.

## Próximos Pasos

1. **Refinamiento del modelo:** Realizar pruebas adicionales para identificar y ajustar hiperparámetros que mejoren la precisión del modelo.
2. **Visualización avanzada:** Crear dashboards interactivos que permitan explorar los factores más relevantes en la predicción.
3. **Integración en sistemas corporativos:** Diseñar una API o integración directa para que Recursos Humanos pueda utilizar las predicciones en tiempo real.
4. **Ampliación del dataset:** Incluir datos históricos o externos que puedan enriquecer las predicciones.
5. **Automatización del pipeline:** Automatizar el preprocesamiento y el entrenamiento para facilitar actualizaciones periódicas del modelo.

---