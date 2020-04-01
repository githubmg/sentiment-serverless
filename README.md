# Sentiment analysis

En esta notebook utilizaremos un dataset abierto que contiene opiniones de los alumnos sobre un curso.  
Si bien existen muchas técnicas para la clasificación de text, vamos a utilizar una de las técnicas más rápidas y sencillas: <a href='https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html'> Multinomial Naive Bayes </a>. 

El objetivo de este ejercicio es crear de forma rápida un microservicio que permita consumir dicho modelo utilizando una arquitectura serverless. 