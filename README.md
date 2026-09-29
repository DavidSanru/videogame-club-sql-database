# Videogame Club Database

Diseño e implementación de una base de datos relacional para un club de
videojuegos: modelado entidad-relación, carga de datos desde CSV, consultas
SQL, triggers y procedimientos almacenados, con pruebas de cada uno.

**Tecnologías:** SQL ([MySQL/PostgreSQL]), Python, Jupyter Notebook

## Modelo entidad-relación
![Modelo E-R](docs/modelo_er.png)

## Contenido
| Archivo | Descripción |
|---|---|
| `Modelo entidad relacion.drawio` | Diagrama E-R de la base de datos |
| `club-games.csv` | Datos originales del club de videojuegos |
| `practica_1.ipynb` | Limpieza y transformación del CSV e inserción de los datos |
| `creaciontablas.sql` | Creación de las tablas del modelo |
| `queries.sql` | Consultas SQL |
| `triggers.sql` | Triggers implementados |
| `procedures.sql` | Procedimientos almacenados |
| `testing.sql` | Pruebas de triggers y procedures |
| `main.py` | [qué hace] |

## Cómo ejecutarlo
1. Crear las tablas: `creaciontablas.sql`
2. Cargar los datos: ejecutar `practica_1.ipynb`
3. Crear triggers y procedures, y probarlos con `testing.sql`

## Autores
David Santiago Ruiz
Brian Bedoya Piedrahita
