# Proyecto_tienda_online

**Estudio de Análisis de Datos** de la información recabada en la primera presentación de este proyecto.

En este punto lo que vamos a mostrar es como hemos creado una Base de Datos en SQL, para lo cual hemos usado SQLite3.

A partir de la información guardada en la Base de Datos, vamos a realizar un estudio sobre las características de los *productos*, *fecha* de "compra" (estamos considerando que la fecha de compra es la fecha en la que el usuario ha puesto un comentario, lo cual no es exacto) y de los *precios*.

Partimos inicialmente del [repositorio de Webscrapping](https://github.com/75Engel/Webscrapping_tienda_online) que presentamos el pasado año, donde se realizo la obtención de los datos.

**Nota:** 

La información que estamos utilizando es la obtenida en su momento con el arañado de la página web.

---
## Estructura y Metodología:

Este proyecto está fragmentado en 4 partes o Notebooks:

[1. Obtención y tratamiento de los datos.](src/Notebook/01_Scrape.ipynb)

Este Notebook es el que presentamos en el desarrollo de la primera parte de este proyecto, se presenta a modo testimonial.

[2. Tratamiento de los datos de texto.](src/Notebook/02_Engineering.ipynb)

Este Notebook presenta como la información obtenida, la hemos tratado con las librerías Pandas, datetime, RegEx y SpaCy.

[3. Generación de base de datos.](src/Notebook/03_sql.ipynb)

Este Notebook muestra el diseño de la Base de datos y su primera carga.

Este Notebook utiliza para esta proceso las librerías de python pandas y sqlite3.

[4. Visualización de datos.](src/Notebook/03_sql.ipynb)

En este mismo Notebook vamos a realizar el EDA de los datos cargados, a partir de comandos de SQL, datetime, pandas, seaborn y matplotlib.

---
## What's next?:

Durantes este semestre de 2024, hemos desarrollado los scripts necesarios para automatizar los procesos de obtención de datos y carga de datos en la Base de datos.

Esta información no aparece en este repositorio.

La intención con este proceso es obtener la información necesaria para poder realizar modelado de datos y dar respuesta al motivo de este proyecto, dar una experiencia mejorada a los usuarios de la página web en relación con la publicidad que recibe de los productos.

Este proceso parte del proyecto se plantea realizar en el segundo semestre de este año.
