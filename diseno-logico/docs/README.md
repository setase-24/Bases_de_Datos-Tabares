# Resumen – Diseño lógico de bases de datos

## 1. Objetivo del diseño lógico
El diseño lógico transforma el modelo conceptual (Diagrama Entidad–Relación)
en un esquema relacional basado en tablas.

## 2. Modelo utilizado
Empleamos el modelo relacional, el cual organiza la información en:
- Tablas
- Claves primarias (PK)
- Claves foráneas (FK) (Ajenas mencionadas en el video)

## 3. Reglas principales de transformación

### Entidad → Tabla
Cada entidad del modelo ER se convierte en una tabla.

### Atributos → Columnas
Los atributos pasan a ser columnas dentro de la tabla.

### Atributo clave → Clave primaria
El atributo identificador se convierte en PK.

### Relación 1:N
Se añade la clave primaria del lado 1 como clave foránea en la tabla del lado N.

### Relación N:M
Se crea una tabla intermedia que contiene:
- Las claves primarias de ambas entidades
- Los atributos propios de la relación
- Una clave primaria compuesta

## 4. Conclusión
El diseño lógico nos permite mantener coherencia entre la información
y la estructura final de la base de datos.

