# Conjuntos de Datos y Notebooks de Análisis
Este repositorio contiene tres conjuntos de datos diferentes junto con dos archivos de Jupyter Notebook para análisis exploratorio y trabajo final. A continuación se describe cada conjunto de datos y los notebooks disponibles:

## 1. Producción de Carne Bovina en Argentina (`produccion-de-carne-bovina.csv`)
Este dataset contiene información sobre la producción de carne bovina en Argentina, proporcionando detalles a nivel provincial y departamental, así como información financiera y de gestión relacionada con la producción ganadera. El dataset incluye variables como provincia, año, modelo de producción, ingreso neto, eficiencia de stock, producción por hectárea, entre otras.

### Variables Potencialmente Interesantes
Algunas variables que podrían resultar especialmente relevantes para el análisis incluyen:

* `provincia` y `departamento`: Para analizar patrones geográficos en la producción de carne bovina.
* `año` y `mes`: Para detectar tendencias temporales en la producción.
* `margen_bruto_($/ha)`, `resultado_neto_($/ha)` e `ingreso_neto_($/ha)`: Para evaluar la rentabilidad de la producción.
* `eficiencia_stock_(%)`: Para medir la eficiencia en la gestión del ganado.
* `producción_(kg/ha)`: Para evaluar el rendimiento de la producción de carne.
* `destete_(%)` y `carga_(kg/ha)`: Para analizar la cría y manejo del ganado.

### Fuente de Datos
El dataset original está disponible en [Kaggle](https://www.kaggle.com/datasets/anggyelarez/produccin-de-carne-bovina-en-argentina?resource=download).

## 2. Ventas de Departamentos en la Ciudad Autónoma de Buenos Aires (`departamentos-en-venta-2001.csv`)
Este dataset contiene información sobre las ventas de departamentos en la Ciudad Autónoma de Buenos Aires, incluyendo detalles sobre ubicación, tamaño, precio en dólares y características del departamento. El dataset incluye variables como barrio, metros cuadrados, precio en dólares, número de ambientes, entre otras.

### Variables Potencialmente Interesantes
Algunas variables que podrían resultar especialmente relevantes para el análisis incluyen:

* `M2`, `DOLARES` Y `U_S_M2`: Para evaluar la relación entre el tamaño del departamento y su precio.
* `AMBIENTES` y `BAÑOS`: Para entender la distribución del espacio interior del departamento.
* `ANTIGUEDAD`: Para analizar la preferencia por departamentos nuevos o usados.
* `BARRIO` y `COMUNA`: Para identificar áreas de mayor demanda y precios.
* `BAULERA`, `COCHERA`, `LAVADERO` y `TERRAZA`: Para evaluar la disponibilidad de comodidades adicionales en los departamentos.
* `LAT` (Latitud) y `LON` (Longitud): Para visualizar la distribución espacial de las ventas de departamentos en la ciudad.

### Fuente de Datos
El dataset original está disponible en [Data Buenos Aires](https://data.buenosaires.gob.ar/dataset/departamentos-venta/resource/juqdkmgo-701-resource).

## 3. Ventas de Autos y Tendencias de Mercado (`car_prices.csv`)
Este dataset contiene información sobre las ventas de autos, incluyendo detalles como marca, modelo, año, precio de venta y características del vehículo. Lamentablemente el dataset es demasiado pesado para subirlo a la plataforma, por lo que subi el archivo comprimido como .zip.

### Variables Potencialmente Interesantes
Algunas variables que podrían resultar especialmente relevantes para el análisis incluyen:

* `make` y `model`: Para analizar la popularidad de diferentes marcas y modelos en el mercado de autos usados.
* `year`: Para evaluar la demanda y los precios en función del año de fabricación.
* `bosy` y `transmission`: Para entender las preferencias del consumidor en términos de características del vehículo.
* `odometer` y `condition`: Para determinar cómo afectan estos factores al precio de venta.
* `color` e `interior`: Para analizar las preferencias de color en los autos vendidos.
* `sellingprice` y `mmr`: Para evaluar si los vehículos se venden por encima o por debajo de su valor de mercado.
* `saledate`: Para identificar tendencias estacionales en las ventas de autos.

### Fuente de Datos
El dataset original está disponible en [Kaggle](https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data).

## Notebooks de Análisis
El repositorio también contiene dos archivos de Jupyter Notebook:

1. Visualización+Reyes.ipynb: Este notebook contiene un análisis exploratorio inicial de datos y visualización para el primer conjunto de datos.
2. ProyectoDS_Partel_+Reyes.ipynb: Este notebook contiene el trabajo final que integra análisis númerico y grafico, para responder preguntas de interes propuestas para el primer conjunto de datos.
