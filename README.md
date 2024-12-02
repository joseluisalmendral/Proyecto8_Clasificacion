
# 🔮 Predicción Abandono Empleados

<img src="https://2pblsgi9dvrv.b-cdn.net/w_1674,h_810/3d7dsjcota06-blog-employee-engagement.webp">

## 📋 Descripción del Proyecto

El principal desafío de este proyecto es abordar una de las preguntas más importantes para cualquier departamento de Recursos Humanos: **¿qué empleados tienen más probabilidades de quedarse en la empresa y cuáles podrían decidir irse?**  
Para lograr esto, se ha desarrollado un modelo de machine learning capaz de predecir si un empleado permanecerá en la empresa o decidirá marcharse en función de un conjunto de datos sobre empleados de IBM. El objetivo es proporcionar a las organizaciones una herramienta predictiva para retener talento y diseñar estrategias más efectivas en la gestión de personal.

## Preguntas a responder

Las preguntas que este estudio responde, se encuentran en el README.md del siguiente repo --> https://github.com/DataScienceOct24/Proyecto8-Clasificacion

## ⚙️ Instalación Entorno

Clonar repositorio y ejecutar el siguiente comando:

```bash
pip install -r requirements.txt
```

## 🗂️ Estructura Proyecto

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
├── requirements.txt            # Dependencias del proyecto.
├── README.md                   # Documentación del proyecto.
└── .gitignore                  # Archivos y directorios ignorados por Git.

```

## 🔍 Puntos a Remarcar

- Se ha incorporado un archivo ```config.py``` en la raiz de los notebooks para así de una forma super molona tener los encabezados de nuestros notebooks limpios.

## 🧾 Conclusiones

Las conclusiones específicas del análisis y respuestas que respondes a las preguntas planteadas inicialmente, se encuentran en el archivo `notebooks/iteracion1/4_predicciones.ipynb`.

## 🛠️ Próximos Pasos

- **Refinamiento del modelo:** Realizar pruebas adicionales para identificar y ajustar hiperparámetros que mejoren la precisión del modelo, eliminación de variables de no mucha importancia, categorización de otras que se nan quedado sin, etc.

- **Realizar Balance:** Realizar Balance sobre nuestra variable predictora para así obtener mejores métricas a la fuera del training.