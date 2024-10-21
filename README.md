# 🏢 Laboratorio 4.1: Consultas Avanzadas en MongoDB: Análisis de Empresas

## 📖 Descripción
Este laboratorio se enfoca en realizar consultas avanzadas en MongoDB para obtener información sobre empresas a partir de diversas condiciones y restricciones. El objetivo es dominar las consultas complejas y de agregación para obtener insights valiosos sobre las empresas, como número de empleados, valoración, adquisiciones, y fechas de fundación.

## 🗂️ Estructura del Proyecto

El proyecto incluye los siguientes archivos y directorios:

```
├── companies.json       # Datos en formato JSON para la colección de empresas
├── lab.ipynb            # Notebooks de Jupyter con las consultas y soluciones del laboratorio
├── README.md            # Descripción del proyecto
```

## 📑 Ejercicios la lab

1. Todas las empresas cuyo nombre sea `'Babelgum'`, recuperando solo su campo `name`.
2. Empresas con más de 5000 empleados, limitando la búsqueda a 20 empresas y ordenándolas por número de empleados.
3. Empresas fundadas entre 2000 y 2005, recuperando solo los campos `name` y `founded_year`.
4. Empresas con una valoración de más de 100,000,000 que fueron fundadas antes de 2010, recuperando los campos `name` e `ipo`.
5. Empresas con menos de 1000 empleados y fundadas antes de 2005, ordenadas por número de empleados, y limitando a 10 empresas.
6. Empresas que no incluyen el campo `partners`.
7. Empresas con un valor nulo en el campo `category_code`.
8. Empresas con al menos 100 empleados pero menos de 1000, recuperando los campos `name` y `number_of_employees`.
9. Ordenar las empresas por su precio de IPO en orden descendente.
10. Recuperar las 10 empresas con más empleados, ordenadas por el número de empleados.
11. Empresas fundadas en el segundo semestre del año, limitando la búsqueda a 1000 empresas.
12. Empresas fundadas antes del año 2000 con un monto de adquisición superior a 10,000,000.
13. Empresas adquiridas después de 2010, ordenadas por monto de adquisición, recuperando los campos `name` y `acquisition`.
14. Ordenar las empresas por su `founded_year`, recuperando los campos `name` y `founded_year`.
15. Empresas fundadas en los primeros siete días del mes, ordenadas por su `acquisition price` en orden descendente, limitando la búsqueda a 10 documentos.
16. Empresas en la categoría `'web'` con más de 4000 empleados, ordenadas por la cantidad de empleados en orden ascendente.
17. Empresas cuyo monto de adquisición es superior a 10,000,000 y cuya moneda es `'EUR'`.
18. Empresas adquiridas en el primer trimestre del año, limitando la búsqueda a 10 empresas y recuperando los campos `name` y `acquisition`.

## 🛠️ Instalación y Requisitos

Este proyecto utiliza **MongoDB** para la base de datos y **Python** para ejecutar las consultas. Las dependencias incluyen:

- `pymongo` para conectarse y realizar operaciones con MongoDB.
- `pandas` para manejar los datos en Python.
  
Para instalar las dependencias, ejecuta:

```bash
pip install pymongo pandas
```

## 📊 Resultados y Conclusiones

- Las consultas avanzadas en MongoDB permiten obtener insights detallados sobre empresas, como adquisiciones, tamaño y fechas de fundación.
- La flexibilidad de MongoDB para realizar búsquedas cruzadas y consultas agregadas es clave para análisis complejos.

## 🔄 Próximos Pasos
- Continuar optimizando las consultas para grandes conjuntos de datos.
- Implementar nuevas consultas de agregación y filtrado más complejas para ampliar el análisis.


## 🙌 Créditos

Este proyecto fue desarrollado como parte de una práctica que incorpora la mejora de uso de mongo.
