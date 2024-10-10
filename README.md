# Articulos periodisticos en espa;ol
Este repositorio contiene una colección extensa de noticias en formato JSON, en idioma español. Estos archivos pueden ser utilizados para entrenar modelos de Machine Learning.

Cada archivo sigue el siguiente formato:
{
"Id":""
"Author":"",
"Title":"Titulo",
"Content":"",
"PublishedDate":1575705600,
"Keywords":[""]
}

## all_articles_token.csv
Csv con noticias sobre feminicidios y noticias regulares, el contenido de la noticia esta pre-procesado por un lematizador y se han eliminado las stopwords.

## balanced_articles.csv
Csv con noticias sobre feminicidios y noticias regulares, el contenido de la noticia esta pre-procesado por un lematizador y se han eliminado las stopwords. El # de noticias por cada grupo es exactamente la misma cantidad:
486 articulos sobre fmeinicidios y no sobre feminicidios.

## news.db
Base de datos de SQLITE, puedes cargarla con https://sqliteonline.com/ y mirar el contenido, te dejo SQL:

![image](https://github.com/user-attachments/assets/401192e6-fe06-4596-94b7-005dfd23f1bb)


Favor de ver el primer release de este repo:

https://github.com/DanyelMorales/coleccion_de_noticias_en_espanol/releases/tag/v1.1.0
