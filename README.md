# 🛒 Laboratorio 4.1: Gestión de Campañas de Marketing en MongoDB

## 📖 Descripción
Este laboratorio se centra en la creación y manipulación de una base de datos MongoDB para una empresa de comercio electrónico que gestiona campañas de marketing, locales, productos y clientes. El objetivo es optimizar la gestión de datos a través de consultas y operaciones avanzadas en MongoDB, permitiendo analizar mejor la información para tomar decisiones informadas.

## 🗂️ Estructura del Proyecto

El proyecto incluye los siguientes archivos y directorios:

```
├── campaigns.json       # Datos en formato JSON para la colección de campañas
├── lab.ipynb            # Notebooks de Jupyter con las consultas y soluciones del laboratorio
├── README.md            # Descripción del proyecto
```

## 📑 Ejercicios Realizados

### Ejercicio 1: Creación de la Base de Datos y Colecciones
- Carga del archivo JSON `campaigns.json`.
- Creación de la base de datos `EcommerceDB`.
- Inserción de datos en las colecciones correspondientes.

### Ejercicio 2: Consultas Básicas
- Consultas como encontrar locales de tipo "Warehouse" y productos fuera de la categoría "Electronics".
- Búsqueda de locales y clientes con `premise_id` y otros de diferentes cosas.

### Ejercicio 3: Proyecciones y Ordenamiento
- Ejemplos de proyecciones como mostrar solo ciertos campos (`premise_id`, `premises_type`).
- Ordenamiento de productos por nombre y paginación de clientes.
- Encuentra los primeros 5 clientes.

### Ejercicio 4: Consultas Avanzadas
- Consultas de agrupación, búsquedas cruzadas, y proyecciones más complejas.
- Ejemplos incluyen campañas que comenzaron en 2021 y búsqueda de productos que contienen la letra "a", entre otros

## 🛠️ Instalación y Requisitos

Este proyecto utiliza **MongoDB** para la base de datos y **Python** para ejecutar las consultas. Las dependencias incluyen:

- `pymongo` para conectarse y realizar operaciones con MongoDB.
- `pandas` para manejar los datos en Python.
  
Para instalar las dependencias, ejecuta:

```bash
pip install pymongo pandas
```

## 📊 Resultados y Conclusiones

- La implementación de MongoDB permite consultas rápidas y eficientes sobre grandes volúmenes de datos.
- Las proyecciones y agregaciones realizadas optimizan la recuperación de datos para análisis específicos.
- La capacidad de realizar búsquedas cruzadas y filtrado por criterios avanzados facilita la toma de decisiones empresariales.

## 🔄 Próximos Pasos
- Añadir más datos históricos para realizar análisis más profundos.
- Implementar técnicas avanzadas de optimización de consultas en MongoDB.

## 🙌 Créditos

Este proyecto fue desarrollado como parte de una práctica que incorpora la mejora de uso de mongo.
