# Glass Classification
![baner](https://img.freepik.com/vector-premium/machine-learning-banner-web-icon-set-mineria-datos-algoritmo-red-neuronal_35632-107.jpg?w=2000)

Este repositorio contiene un proyecto de clasificación de vidrio que utiliza un conjunto de datos de identificación de vidrio de UCI. El objetivo principal de este proyecto es desarrollar un modelo de aprendizaje automático para clasificar diferentes tipos de vidrio en función de varias características, como el índice de refracción y los contenidos de diferentes elementos químicos.

## Conjunto de Datos

El conjunto de datos utilizado en este proyecto consta de las siguientes características:

- **RI (Índice de refracción)**: El índice de refracción del vidrio.
- **Na (Sodio)**: El contenido de sodio en el vidrio, medido en porcentaje de peso en el óxido correspondiente.
- **Mg (Magnesio)**: El contenido de magnesio en el vidrio.
- **Al (Aluminio)**: El contenido de aluminio en el vidrio.
- **Si (Silicio)**: El contenido de silicio en el vidrio.
- **K (Potasio)**: El contenido de potasio en el vidrio.
- **Ca (Calcio)**: El contenido de calcio en el vidrio.
- **Ba (Bario)**: El contenido de bario en el vidrio.
- **Fe (Hierro)**: El contenido de hierro en el vidrio.

El objetivo es predecir el "Tipo de vidrio", que es una variable objetivo discreta con siete posibles valores:

1. Building Windows Float Processed
2. Building Windows Non-Float Processed
3. Vehicle Windows Float Processed
4. Vehicle Windows Non-Float Processed (no presente en esta base de datos)
5. Containers
6. Tableware
7. Headlamps

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

- **`data/`**: Contiene el conjunto de datos en formato CSV.
- **`notebooks/`**: Aquí encontrarás Jupyter notebooks que explican el proceso de exploración de datos, entrenamiento de modelos y evaluación.
- **`models/`**: Almacena los modelos entrenados.
- **`app/`**: Contiene el código para la aplicación web Django que despliega el modelo entrenado para su uso en tiempo real.
- **`requirements.txt`**: Lista de las bibliotecas de Python necesarias para ejecutar el proyecto.
- **`LICENSE`**: Licencia del proyecto.
- **`README.md`**: Este archivo que proporciona información sobre el proyecto.

## Ejecución del Proyecto

Si deseas ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona este repositorio:

```bash
git clone https://github.com/tuusuario/glass-classification.git
cd glass-classification
```

2. Crea y activa un entorno virtual (se recomienda usar `venv` o `conda`):

```bash
python -m venv venv
source venv/bin/activate  # En Windows, usa "venv\Scripts\activate"
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Explora los notebooks en la carpeta `notebooks/` para entender el proceso de análisis de datos y entrenamiento del modelo.

5. Ejecuta la aplicación web Django para desplegar el modelo entrenado:

```bash
cd app
python manage.py runserver
```

La aplicación estará disponible en `http://localhost:8000/` en tu navegador web local.

¡Disfruta explorando y trabajando en este proyecto de clasificación de vidrio!
