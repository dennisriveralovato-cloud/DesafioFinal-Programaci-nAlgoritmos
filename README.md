# DesafioFinal-ProgramacionAlgoritmos
# Sistema Integral de Gestión de Biblioteca Universitaria

Proyecto desarrollado en C# como aplicación de consola para el desafío final de la materia Programación de Algoritmos.  
El sistema permite administrar libros, usuarios y préstamos de una biblioteca universitaria mediante menús interactivos y persistencia de datos usando archivos.

# Integrantes

## Integrante 1
- Nombre: Cristian Márquez
- Carné: MP261720

## Integrante 2
- Nombre: Dennis Rivera
- Carné: RL261460

# Descripción del Proyecto

El Sistema Integral de Gestión de Biblioteca Universitaria permite gestionar los procesos básicos de una biblioteca universitaria mediante una aplicación de consola desarrollada en C#.

El sistema incluye:

- Registro de libros
- Búsqueda de libros
- Eliminación de libros
- Registro de usuarios
- Búsqueda de usuarios
- Registro de préstamos
- Registro de devoluciones
- Reportes generales
- Persistencia de datos mediante archivos

# Tecnologías Utilizadas

- Lenguaje: C#
- Plataforma: .NET 6
- Tipo de aplicación: Console Application
- IDE recomendado: Visual Studio 2022

# Estructuras de Programación Utilizadas

El proyecto implementa las siguientes estructuras vistas durante el ciclo:

- Estructuras secuenciales
- if-else
- switch-case
- for
- while
- do-while
- Arreglos
- Matrices
- Manejo de cadenas
- Structs
- Manejo de archivos
- Validaciones
- Try-Catch

# Structs Utilizados

## Libro
Contiene:
- código
- título
- autor
- editorial
- año
- categoría
- cantidad disponible

## Usuario
Contiene:
- carné
- nombre
- carrera
- correo
- teléfono
- estado

## Prestamo
Contiene:
- carné de usuario
- código de libro
- fecha de préstamo
- fecha de devolución
- estado
