# PyCaret y Streamlit

Construyendo un clasificador de vinos con PyCaret y usando Streamlit para crear e implementar la aplicación web

![Portada](Vinos.jpeg)

La creación e implementación de un modelo de aprendizaje automático nunca ha sido tan fácil. En este momento, tenemos muchos marcos y bibliotecas que nos permiten crear modelos de aprendizaje automático con solo unas pocas líneas de código. Entre todos ellos, PyCaret es uno de los mejores. Para crear e implementar una aplicación web para nuestro proyecto de ciencia de datos, Streamlit se ha vuelto muy popular últimamente.

En este artículo, utilizaremos estas dos bibliotecas para crear una aplicación web de ciencia de datos. Usaremos PyCaret para construir un clasificador de calidad de vino. A continuación, usaremos Streamlit para crear e implementar este clasificador de vinos. Se sorprenderá de lo fácil y rápido que es construir el clasificador e implementar la aplicación web con estas dos bibliotecas. ¡Entonces empecemos!

# Introducción a la aplicación a desarrollar.

Como hemos comentado, el objetivo de este articulo es crear un modelo de aprendizaje automático usando Pycaret y Streamlit. Para ello vamos a estructurar el proyecto de la siguiente manera:

- Cargar y procesar los datos
- Construir el modelo de clasificador usando Pycaret.
- Crear la aplicación wweb con Streamlit

# Cargar y procesar los datos

Los datos que usaremos en este artículo son el conjunto de datos de calidad del vino. Este conjunto de datos consta de 1599 instancias con 12 características. Carguemos el conjunto de datos con Pandas.

![Portada](datos-vinos.png)
