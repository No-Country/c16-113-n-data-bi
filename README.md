
![Logo](https://github.com/No-Country/c16-113-n-data-bi/blob/804cd3081162986cb7c9461da39be35f65eeefec/resources/Bannerreadme.png)

## <img width="30" height="30" src="https://github.com/No-Country/c16-113-n-data-bi/assets/65770894/91256d1f-e969-417d-8b17-b793573bf236" alt="crowd"/> Integrantes del equipo

- [**TL**: Sofia Baeza Brandauer](https://www.linkedin.com/in/sofia-brandauer/)
- [**Data Engineering & ETL Dev**: Elías Almada](https://www.linkedin.com/in/elias-almada-795a54158/)
- [**Data & BI Analyst**: María José Atencio](https://www.linkedin.com/in/maria-jose-atencio-96a8761aa/)
- [**Data & BI Analyst**: José Alexander Gómez Tapia](https://www.linkedin.com/in/josealexandergt?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
- [**PM**: Hernán Delgado](https://www.linkedin.com/in/hern%C3%A1n-delgado?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## :bar_chart: Descripción de Proyecto

A partir de las distintas iniciativas planteadas para esta simulación, nuestro equipo decidió realizar un tablero en PowerBI con el fin de llevar adelante el análisis de un dataset que contiene datos de la plataforma de streaming Netflix.

El fin del mismo es responder una serie de preguntas de negocio:

- **Cuántos títulos hay disponibles?**
- **Cómo ha cambiado la cantidad de títulos disponibles en Netflix con el tiempo?**
    - Títulos más populares por País?
- **Qué géneros son los más populares?**
- **Qué tipo de contenido (películas, series) es el más popular?**
    - Películas más populares?
    - Series más populares?
    - Cuáles son los Directores más Populares?
- **Cómo varía la popularidad del contenido en cierto tiempo por país ?**
- **Qué países tienen la mayor cantidad de usuarios?**
- **Cómo ha cambiado la cantidad de usuarios de Netflix con el tiempo?**
    - Qué tipo de contenido ven los usuarios?
    - Cuanto Tiempo ven Netflix los Usuarios?
    - En que dispositivos ven Netflix?
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## :computer: Stack de tecnologías

- 🔧 **Python**: Análisis, normalización y transformación del dataset original. 
- 📝 **MySQL**: Creación de la base de datos para la ingesta de datos de la herramienta de visualización.
- 📑 **PowerBI**: Visualización de los datos para su análisis visual e identificación de tendencias.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## ➡️ Proceso y metodología

- ▶️ Se utilizó la metodología de sprints para realizar las distintas tareas, comenzando por el primer sprint en el cual se realizó la eleccion y descarga del dataset desde la plataforma Kaggle, su posterior análisis, normalización y limpieza. A continuación se transformó el dataframe creado en python a una base de datos MySQL para que la ingesta de datos desde PowerBI se hiciera mas sencilla y a la vez mas estructurada.

- ▶️ El segundo sprint constó de la conexión de la base de datos MySQL con PowerBI y la creación de una plantilla para el tablero, a fin de tener todos los filtros y una uniformidad visual en las distintas pantallas del tablero final.

- ▶️ El tercer y último sprint constó de la creación del tablero en si mismo, su análisis y la búsqueda de tendencias y relaciones relevantes para el fin de contestar las preguntas de negocio planteadas inicialmente.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🛑 Resultados

El proyecto ha permitido obtener una serie de insights sobre la plataforma Netflix, como por ejemplo:

- Los géneros más populares entre los usuarios.
- La distribución de las películas y series por país de origen.
- La evolución del número de usuarios a lo largo del tiempo.
- La relación entre la calificación de una película o serie y su número de visualizaciones.
  
## 🪜 Conclusiones

El proyecto ha demostrado el potencial de Power BI para la visualización de datos y la obtención de insights a partir de grandes conjuntos de datos.
