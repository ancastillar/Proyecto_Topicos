# Proyecto_Topicos


# 1. Motivación
Realizar correctamente el pronóstico de las ventas de ciertos productos es de gran relevancia para cierto tipo de empresas ya que así pueden tener una medición de la demanda de sus productos. Al tener una idea de la demanda de sus productos, las empresas pueden adelantarse a las necesidades de sus clientes y de esta manera tomar decisiones de negocio. Algunas de las decisiones de negocio usuales son: **asegurarse de contratar el número suficiente de empleados, tener un presupuesto aproximado de los gastos operativos y realizar el correcto restock de los productos**. Por lo anterior, realizar malos pronósticos conduce a pérdidas monetarias en la empresa, como los gastos generados al acumular un excedente de productos en épocas de baja demanda o la pérdida de beneficios
cuando hay escasez de suministros y hay una gran demanda de estos. 

Este trabajo se dividirá en dos partes:

1. Se realizará un pronostico del volumen de ventas para una de las tiendas de Walmart.

2. Se evaluará la satisfacción de los clientes de Walmart mediante análisis de sentimientos de tweets.

**Esto con el objetivo de obtener una perspectiva más completa de las necesidades del cliente y permitir una mejor toma de decisiones.**

# 2. Planteamiento del problema

**Datos**

**Pronóstico**

Para realizar los pronósticos de las ventas, se emplearán los datos de la competencia de Kaggle: https://www.kaggle.com/c/m5-forecasting-accuracy/data. La tarea consiste en predecir el volumen de ventas (es decir, el número de productos vendidos) para 3.049 productos de Walmart y para cada una de sus tiendas, durante un período de 28 días. Los productos abarcan 3 categorías (Hobbies, Hogar, Alimentación) y 7 departamentos en 3 estados (CA, TX, WI). En resumen, la entrada de nuestro algoritmo es
una serie temporal del volumen de ventas de cada producto durante los últimos 2 años. Finalmente, emplearemos una red neuronal para poder realizar el pronóstico.

**Análisis de sentimiento**

Por otra parte, para evaluar la satisfacción del cliente se emplearán los tweets, que se extraeran mediante la API Tweepy . Los tweets de interés serán los relacionados con Walmart y serán seleccionados según la ubicación de la tienda de interés para el pronóstico.

Por otra parte, debido a que la extracción de tweest se realiza en tiempo real se creó una base de datos en la nube (mediante los recursos ofrecidos por Amazon WS) que almacernará nuestros datos mediante se iban extrayendo.

# 5. Fases del proyecto

* Cronstrucción de la fuente de datos para analizar: realizar joins y colocar en el formato correcto para realizar los modelos de pronóstico
* Exploración y entendiemiento de los datos
* Revisión de literatura
* Planteamiento de los modelos de pronóstico
* Evaluación de los modelos
* Construcción de la base de datos con los Tweets (en tiempo real y por ubicación geográfica) de los clientes de Walmart
* Revisión de la literatura para modelos de clasificación de emociones
* Planteamiento del modelo
* Evaluación
* Aplicación con los datos en tiempo real

# 4 Contenido del Git

