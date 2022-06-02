![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Data Cleaning and Manipulation with Pandas
**Javiera Córdova - Data Analytics Part Time Abril 2202**

## Introducción

Este proyecto tiene por objetivo limpiar un archivo que viene sucio, utilizando todas las técnicas, métodos, funciones, entre otros, vistas en clases.

## Archivos

* **attacks** Archivo a limpiar.
* **sharkattackmodified** Archivo csv semi limpio.
* **shark_attack** Notebook Jupyter con códigos.
* **Archivo ``README.md``**

## Workflow

1. Lo primero fue importar el archivo en Python y entender de qué información estaba compuesto. Con lo anterior me refiero a: columnas, filas, datos nulos, información por columna, forma, etc.
2. Con el % de datos nulos por columnas, eliminé 2 columnas en las cuales más del 99% de los datos eran datos nulos. Lo mismo hice para las filas que sólo tenían valores nulos.
3. Luego de eliminar filas y columnas cuya información no iba a ser de utilidad, renombré las columnas para poder trabajar de forma más fácil el dataframe.
4. Lo que vino posteriormente fue ir limpiando columna por columna de acuerdo a la información. La mayoría de los valores nulos fueron reemplazados por 'unknown', y otros datos fue posible inferir y reemplazar.
5. Al ser una database bastante sucia, el objetivo es seguir trabajando en ella.
