# Modelo de predicción del abandono de empleados de una empresa

## :ok_man: Autores

-   Alejandro López Sancho
-   Javier Rosales Lozano

Última modificación: 01/09/2025
Grupo 11

## :globe_with_meridians: Descripción

Trabajo de prácticas (2024-2025) para la asignatura de Aprendizaje Automático del Grado de Ingeniería Informática.

Universidad Carlos III de Madrid.

## :book: Resumen

Estudio de un problema de abandono de trabajos en una empresa mediante técnicas de Machine Learning y construcción, ajuste y evaluación de modelos que predigan los resultados a partir de un dataset de empleados y ciertas características.

El proyecto consta de dos Jupyter Notebooks desarrollados consecutivamente:

<table>
  <thead>
    <tr>
      <th>Cuadernos</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a src="employee-attrition-prediction" />employee-attrition-competition</td>
      <td>
        Estudio del dataset, preprocesado de datos, construcción<br>de modelos de ML simples y avanzados, ajuste de<br>hiperparámetros, entrenamiento y evaluación de modelos,<br>y construcción del modelo final más predictivo.
      </td>
    </tr>
    <tr>
      <td><a src="employee-attrition-competition" />employee-attrition-competition</td>
      <td>
        Importación del modelo anterior y predicción de datos de<br>competición.
      </td>
    </tr>
  </tbody>
</table>

## :construction: Estructura del proyecto

```plaintext
employee-attrition-prediction/
├── data/                                         # Conjuntos de datos y predicciones
│   ├── attrition_available_data_02.csv.gz        # Dataset inicial
│   ├── attrition_competition_02.csv.gz           # Datos de competición
│   └── predictions                               # Predicciones del modelo final
├── employee-attrition-competition.ipynb          # Cuaderno asociado a la parte 2
├── employee-attrition-prediction.ipynb           # Cuaderno asociado a la parte 1
├── enunciado.pdf                                 # Enunciado de la práctica
├── model.pkl                                     # Modelo final generado
├── requirements.txt                              # Dependencias instaladas
└── README.md                                     # Este archivo
```

## :link: Dependencias

<img src="https://go-skill-icons.vercel.app/api/icons?i=python,jupyter,sklearn,numpy,pandas,matplotlib&theme=dark&titles=true"/>

## :pencil: Requisitos

- Python v3.8 o superior

## :inbox_tray: Instalación y uso

1. __Clonar el repositorio__

```bash
git clone https://github.com/username/myhomie-app.git
```

Reemplaza `username` por tu nombre de usuario de Github.

2. __Crea el entorno e instala todas las dependencias__

```bash
python -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
```
