# Top 50 Films Scraper
## Description

This script scrapes a webpage to extract information about the top 50 highest-ranked films. It collects data such as average rank, film name, release year, and its presence in Rotten Tomatoes' Top 100. The extracted data is then saved into a CSV file and stored in an SQLite database.

### Features
- Extracts film ranking data from a webpage.
- Stores the data in a pandas DataFrame.
- Saves the data as a CSV file.
- Inserts the data into an SQLite database.

### How It Works
1. The script fetches the webpage using `requests`.
2. It parses the HTML using `BeautifulSoup`.
3. It extracts the relevant table rows and stores the data in a DataFrame.
4. The DataFrame is saved as a CSV file.
5. The data is inserted into an SQLite database.

#### Acknowledgments
This project was inspired by the "Data Engineering" course by IBM on Coursera. The concepts and techniques used in this script were learned through this course.

# Scraper de las 50 Mejores Películas
## Descripción
Este script extrae información de una página web sobre las 50 películas mejor clasificadas. Recopila datos como el ranking promedio, el nombre de la película, el año de estreno y su presencia en el Top 100 de Rotten Tomatoes. Luego, los datos extraídos se guardan en un archivo CSV y se almacenan en una base de datos SQLite.
### Características
- Extrae datos de clasificación de películas de una página web.
- Almacena los datos en un DataFrame de pandas.
- Guarda los datos en un archivo CSV.
- Inserta los datos en una base de datos SQLite.

### Cómo Funciona
1. El script obtiene la página web utilizando `requests`.
2. Analiza el HTML con `BeautifulSoup`.
3. Extrae las filas relevantes de la tabla y almacena los datos en un DataFrame.
4. Guarda el DataFrame en un archivo CSV.
5. Inserta los datos en una base de datos SQLite.

#### Agradecimientos
Este proyecto fue inspirado por el curso "Data Engineering" de IBM en Coursera. Los conceptos y técnicas utilizados en este script fueron aprendidos a través de este curso.
