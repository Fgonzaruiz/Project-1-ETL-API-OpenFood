# Project-1-ETL-API-OpenFood
## English:
The following Python code performs an ETL (Extract, Transform, Load) process using the OpenFoodFacts API to compare different food brands based on various criteria.

First, the code imports the necessary libraries, including requests for making API calls and pandas for data manipulation.

Next, the code defines a function for extracting the data from the API. This function makes a GET request to the API endpoint for a specific food category, such as "chocolate," and retrieves the JSON response. The function then parses the JSON data and extracts relevant information, such as brand and nutritional information, and stores it in a pandas DataFrame.

The code then defines a function for transforming the data. This function performs data cleaning and manipulation, such as removing missing or irrelevant data and converting data types. The function also calculates additional metrics, such as the fat-to-protein ratio, for analysis.

Finally, the code defines a function for loading the data into a database or file for further analysis. This function uses the pandas library to write the DataFrame to a CSV file or to a SQL database.

The main function ties all the functions together by calling the extract, transform, and load functions in succession, passing the appropriate parameters. The main function also includes an option for the user to specify different criteria for comparison, such as organic vs non-organic products or products from a specific country.

The code also includes some visualization with matplotlib for better understanding the data and the comparisions.
## Spanish:
El siguiente código de Python realiza un proceso ETL (Extraer, Transformar, Cargar) utilizando la API de OpenFoodFacts para comparar diferentes marcas de alimentación según varios criterios.

En primer lugar, el código importa las bibliotecas necesarias, incluido requests para realizar llamadas a la API y pandas para la manipulación de datos.

A continuación, el código define una función para extraer los datos de la API. Esta función realiza una solicitud GET al punto final de la API para una categoría específica de alimentos, como "chocolate", y recupera la respuesta JSON. La función luego analiza los datos JSON y extrae información relevante, como la marca y la información nutricional, y la almacena en un DataFrame de pandas.

Luego, el código define una función para transformar los datos. Esta función realiza limpieza y manipulación de datos, como eliminar datos faltantes o irrelevantes y convertir tipos de datos. La función también calcula métricas adicionales, como la relación grasa-proteína, para el análisis.

Finalmente, el código define una función para cargar los datos en una base de datos o archivo para un análisis posterior. Esta función utiliza la biblioteca pandas para escribir el DataFrame en un archivo CSV o en una base de datos SQL.

La función principal une todas las funciones llamando a las funciones de extracción, transformación y carga en sucesión, pasando los parámetros adecuados. La función principal también incluye una opción para que el usuario especifique diferentes criterios de comparación, como productos orgánicos vs no orgánicos o productos de un país específico.

El código también incluye algunas visualizaciones con matplotlib para una mejor comprensión de los datos y las comparaciones.

En resumen, este código de Python realiza un proceso completo de ETL utilizando la API de OpenFoodFacts para comparar diferentes marcas de alimentos según varios criterios. Extrae los datos de la API, los transforma limpiando y manipulando los datos, y los carga en un archivo o base de datos para su análisis posterior.
