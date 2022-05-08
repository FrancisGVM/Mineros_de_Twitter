# Mineros_de_Twitter
Reto 4: Mejorando en Twitter la conversación pública sobre la ciencia ¿Cómo crear un detector de mensajes de desconfianza en temas científicos en ambientes controversiales, que podrían ser oportunamente contrarrestados por discurso, narración y explicación desde cuentas de personas expertas y certificadas?

## Clonar Repositorio

Para clonar el repositorio, usar el comando 

``` 
git clone https://github.com/FrancisGVM/Mineros_de_Twitter.git 
```

## Uso del Jupyter Notebook

Para utilizar el código se está proporcionando un [Jupyter Notebook](Minero_Twitter_Solution.ipynb) debidamente comentado para mejor entendimiento. Para poder utilizar este cuaderno es necesario crear una [app de Twitter](https://developer.twitter.com/en/docs/apps/overview) e introducir las [credenciales](https://developer.twitter.com/en/docs/authentication/overview). Es importante [aplicar a una cuenta de desarrollador de Twitter](https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api) previamente. 

### Uso en entornos de desarrollo personal

Para utilizar el cuaderno en un entorno personal (ej. Anaconda), se deben instalar los requisitos, usando el comando 

``` 
pip install -r requirements.txt 
```

## Dataset

El [dataset](./data_repo.csv) utilizado consiste en un conjunto de 500 tweets relacionados con el COVID-19 y las vacunas, obtenidos usando la API de Twitter y la librería `tweepy`. El dataset fue etiquetado manualmente en función de si el tweet era desinformativo o no. 

## Clasificador

El modelo usado para clasificar los tweets fue un clasificador pasivo-agresivo. Este algoritmo pertenece a la familia de algoritmos de Machine Learning. Se decidió prototipar con este algoritmo debido a la ventaja de procesar grandes volúmenes de datos (tweets) y a la natureleza secuencial de aquellos datos en la red social Twitter. A posteriori, incrementar la base de datos es el objetivo siguiente para mejorar el modelo planteado de modo que se pueda identificar tweets desinformativos a más de los relacionados a las vacunas y el Covid-19.  
## Recursos Utilizados

- [tweepy](https://docs.tweepy.org/en/stable/)
- [pandas](https://pandas.pydata.org/pandas-docs/stable/)
- [scikit-learn](https://scikit-learn.org/)
- [wordcloud](https://amueller.github.io/word_cloud/)

## Integrantes del grupo:
- Leonel Cabrera
- Kevin Cárdenas 
- Jorge Gutiérrez 
- Francis Villacrés
