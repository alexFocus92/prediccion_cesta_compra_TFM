# Instacart Market Basket Analysis
Analisis de la cesta de la compra de los usuarios de un supermercado canadiense


Para ejecutar este código es necesario descargar los datos antes de Kaggle, dejo el enlace a continuación:
https://www.kaggle.com/c/instacart-market-basket-analysis/data

He seleccionado este Data Set debido a la gran cantidad de datos
que contiene (más de 3 millones de pedidos), además de tener varias tablas interrelacionadas
usaré tanto métodos supervisados como no supervisados para obtener resultados. Puede resultar
realmente interesante tratar de averiguar que clientes van a recomprar que productos mediante
técnicas de Machine Learning.

## Que es Instacart

Instacart es una compañía estadounidense que opera como un servicio de entrega de comestibles en
el mismo día. Los clientes seleccionan productos a través de una aplicación web de varios minoristas
y el pedido es entregado por un repartidor personal. Hasta fines de 2017, Instacart solo tenía
operaciones y servicios en los Estados Unidos. En noviembre de 2017, la compañía anunció planes
para comenzar la entrega en Toronto y Vancouver.

## Objetivo

Se trata de un conjunto relacional de archivos que describen las órdenes de los clientes a lo largo del
tiempo.
El objetivo de este analisis es predecir qué productos estarán en la próxima orden de un usuario.
El conjunto de datos es anónimo y contiene una muestra de más de 3 millones de pedidos de más
de 200,000 usuarios de Instacart. Para cada usuario, se proporciona entre 4 y 100 de sus pedidos,
con la secuencia de productos comprados en cada pedido.
También se proporciona la semana y la hora del día en que se realizó el pedido, y una medida
relativa del tiempo entre los pedidos.
El objetivo será sacar los artículos que más probablemente puedan reordenar los usuarios (75.000
usuarios) que vienen calificados como test en los datos.
