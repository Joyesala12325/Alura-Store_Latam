# Alura-Store_Latam
Este proyecto forma parte del Challenge 1 de Data Science de Alura LATAM. El objetivo es analizar el desempeño de cuatro tiendas del Sr. Juan para identificar cuál de ellas es la menos rentable y debería ser considerada para su venta. El análisis se realizó en Google Colab utilizando Python y las bibliotecas pandas y matplotlib.


## Estructura del Proyecto

challenge-data-science/
│
├── AluraShop_Analisis.ipynb   # Notebook principal con todos los análisis
└── README.md                  # Este archivo

## Fuente de Datos

Los datos provienen de cuatro archivos CSV alojados en GitHub:

| Tienda   | URL |
|----------|-----|
| Tienda 1 | `tienda_1.csv` |
| Tienda 2 | `tienda_2.csv` |
| Tienda 3 | `tienda_3.csv` |
| Tienda 4 | `tienda_4.csv` |

**Repositorio:** [alura-es-cursos/challenge1-data-science-latam](https://github.com/alura-es-cursos/challenge1-data-science-latam)

Cada archivo contiene las siguientes columnas principales que se usan para el debido análisis:

- `Producto` — Nombre del producto vendido
- `Categoría del Producto` — Categoría a la que pertenece
- `Precio` — Precio de venta del producto
- `Costo de envío` — Costo de envío pagado por el cliente
- `Calificación` — Puntuación del cliente (1 a 5)
- `lat` / `lon` — Coordenadas geográficas de la venta

## Se realizó:

### Una unificación de datos para relacionar las 4  tiendas y asi gacer una comparativa global.

### Análisis de Facturación total por tienda:  Se sumo el total de la columna precio para las 4 tiendas paraa estimar los totales, asi determinamos cual tivo mayor volumen de ventas o de ingresos.

### Análisis de Ventas por categorías: Se agrupo por categorias de producto y se totalizó el ingreso por ventas para determinar que genera mas ingresos y a su vez cuales son las categorias más representativas en terminos de unidades. 

### Análisis de la caligicación promedio por tienda: Se calculo el promedio de la columna Calificación para medir el grado de satisfacción de los clientes.

### Análisis de Costo de envío promedio pro tienda: Se calculo y se determino el costo promedio de envio por cada tienda.

## Generación de gráficos

Se realiza la representación gráfica de todos los análisis sugeridos y se evalia a partir de estos algunas determinaciones.

## Informe final.

Se redacta un texto explicando a qué tienda debe vender el Sr. Juan, teniendo en cuenta todos los factores analizados, como:

Los ingresos totales de las tiendas.

Las categorías de productos más y menos vendidas.

Las calificaciones promedio de los clientes por tienda.

Los productos más y menos vendidos.

El coste de envío promedio para cada tienda.

### Se justifica y se respalda con graficos y  como resultado a los analisis previos de este proyecto.
