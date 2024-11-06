# Analisis-Embudo-de-Ventas-y-Test-A-A-B-e-commerce-de-comida
__Proyecto de análisis a la plataforma de delivery Instacart, análisis exploratiorio y visualización de datos__

<image src="https://github.com/BastianLQ/Analisis-Instacart/blob/main/N3.jpg" alt="Collage de gráficos">

_Fragmentos del notebook, para ver proyecto completo hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Instacart.html)_

## Descripción del Proyecto
Se investigó el comportamiento de usuario para la aplicación de una empresa que comercializa productos alimentarios.

Primero, se estudió el embudo de ventas para descubrir cómo los usuarios y las usuarias llegan a la etapa de compra. Para ello se formularon preguntas relacionadas al comportamiento de los clientes durante su paso por el embudo.

Luego se analizaron los resultados de un test A/A/B, realizado debiido a que al equipo de diseño propuso cambiar las fuentes de toda la aplicación, sin embargo, la gerencia temió que los usuarios y las usuarias pensaran que el nuevo diseño era intimidante. Por ello, decidieron tomar una decisión basada en los resultados del test A/A/B.

Los usuarios se dividieron en tres grupos: dos grupos de control para las fuentes antiguas y un grupo de prueba para las nuevas. Se debió descubrir qué conjunto de fuentes produce mejores resultados. Crear dos grupos A tiene ciertas ventajas. Se puede establecer el principio de que solo se confiará en la exactitud de las pruebas cuando los dos grupos de control sean similares. Si hay diferencias significativas entre los grupos A, esto puede ayudar a descubrir factores que pueden estar distorsionando los resultados. La comparación de grupos de control también indica cuánto tiempo y datos se necesitarán cuando se realicen más tests.

La información para el análisis general y para el análisis A/A/B está en el mismo dataset.
  
## Herramientas Utilizadas
- __Lenguaje de Programación:__ Python.
- __Entorno de Desarrollo:__ Jupyter Notebook.
- __Bibliotecas:__ Pandas, Matplotlib, Plotly, Seaborn, Scipy, Numpy, Math.

## Proceso del Proyecto
- __Descripción de los datos:__ Los datos fueron extraídos de [cinco datasets](https://drive.google.com/drive/folders/11ludpzThvf-xB6LfZW_xzCBK1Z91M_KA?usp=sharing) proporcionados por Instacart _(los datasets están en Drive porque superan el peso máximo permitido de GitHub)_, en esta fase, también, se les da una revisión superficial y se corrigen problemas de importación si es que llegasen a surgir.
- __Preprocesamiento de los datos:__ Se realizaron varias operaciones de limpieza, incluyendo manejo de valores nulos, normalización y formateo de datos.
- __Análisis Exploratorio de Datos (EDA):__ Esta fase se centró en analizar la integridad de los datos y rescatar insights valiosos. Utilizando pandas se exploraron los datos para obtener una comprensión inicial, intermedia y avanzada, y con matplotlib, se generaron visualizaciones para ilustrar los hallazgos clave del análisis.
- __Resultados:__ Se identificaron patrones y tendencias en los datos, como los productos más vendidos y reordenados, y el comportamiento general de los clientes en términos de cantidad de artículos por pedido.

## Relevancia de los descubrimientos
El análisis de datos de Instacart reveló patrones importantes en el comportamiento de compra de los clientes. Estos insights pueden ser utilizados para optimizar las estrategias de marketing, gestión de inventarios y mejorar la experiencia del cliente.

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Instacart.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba.
