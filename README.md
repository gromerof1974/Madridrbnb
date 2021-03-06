# Madridrbnb

Madrid se ha convertido en uno de los destinos predilectos de la inversión inmobiliaria mexicana. El idioma, los lazos culturales entre ambos países, la oferta gastronómica, así como la seguridad jurídica y ciudadana, entre otros atractivos, han provocado el interés del capital inversor mexicano en la capital de España.

Una conocida firma de inversión inmobiliaria mexicana ha pedido realizar un estudio sobre la situación del mercado inmobiliario en la ciudad de Madrid. El problema a resolver es sencillo: ¿Dónde invertir? 

El inversor quiere respuesta a estas preguntas:

- ¿Qué tipo de vivienda comprar?

- ¿En qué zona de la capital?

- ¿Qué destino se le va a dar al inmueble? Entre las opciones de alquiler turístico y tradicional.

Para responder a estas preguntas se utilizan datos de [AirBnB en Madrid](https://www.kaggle.com/rusiano/madrid-airbnb-data).

## Miembros del equipo

- Beatriz Lozano Ballesteros
- Gabriel Romero Fernández

## Descripción de los ficheros

- **data_in/**: contiene los dataset de entrada, excepto el dataset [**review_details.csv**](https://www.kaggle.com/rusiano/madrid-airbnb-data?select=reviews_detailed.csv), que tendrá que descargarse de la red debido a su gran tamaño.

  - **listings.csv**: contiene información sobre los anuncios de alojamientos turísticos de Airbnb en Madrid
  
  - **C5000121.xls**: contiene datos de población por distrito en la ciudad de Madrid

- **data_out/**: contiene los dataset resultado de la limpieza.

  - **listings_clean.csv**
  
  - **reviews_detailed_clean.csv**

  - **population_clean.csv**: resultado de limpiar **C5000121.xls**

- **code/**: 

  - **Madridrbnb.Rmd**: fichero R Markdown que integra el código y la documentación del proyecto
  
  - **UOC_header.html**: cabecera incluida en el fichero Madridrbnb.Rmd

- **doc/**: 

  - **Madridrbnb.html**: compilación del fichero R Markdown en formato html

  - **Madridrbnb.pdf**: respuestas a la práctica 
