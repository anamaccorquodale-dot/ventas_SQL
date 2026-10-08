# ventas_SQL
# Ventas Tech - Proyecto SQL

**Proyecto de Coderhouse - Módulos 3, 4 y 5**

## Descripción

Base de datos de ventas de productos tecnológicos desarrollada en SQL Server.

## Estructura de la base de datos

- **categorias:** categorías de productos.
- **clientes:** información de los clientes.
- **productos:** productos disponibles, vinculados con sus categorías.
- **ventas:** operaciones de venta, vinculadas con clientes y productos.

## Consultas del Módulo 5

1. INNER JOIN entre ventas, clientes y productos para analizar ventas y calcular totales, incluyendo categoría y nombre del cliente.
2. LEFT JOIN para identificar clientes sin ventas.
3. LEFT JOIN para identificar productos sin ventas.
4. UNION ALL para consolidar ventas por canal.

## Cómo ejecutar

1. Abrir SQL Server Management Studio.
2. Ejecutar VENTAS_TECH_DB.SQL para crear la base de datos y cargar los registros.
3. Seleccionar la base de datos Ventas_Tech_DB.
4. Ejecutar m5_consultas_joins.sql.
5. Revisar los resultados de las cuatro consultas.

## Objetivo

Aplicar relaciones entre tablas, JOIN, UNION ALL y funciones de agregación para generar información que pueda utilizarse posteriormente en Power BI.