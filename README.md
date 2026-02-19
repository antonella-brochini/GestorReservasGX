# Gestor de Reservas Online – Proyecto Académico GeneXus

Proyecto desarrollado en el marco del Taller GeneXus de la carrera Analista en Tecnologías de la Información – Universidad ORT Uruguay.

Sistema web para la gestión y venta de entradas para espectáculos, con control de disponibilidad de asientos, gestión de precios y generación de tickets en PDF.

---

## 🎯 Objetivo del sistema

Permitir la administración integral de eventos, ventas de entradas y control de capacidad por sector, asegurando consistencia de datos y reglas de negocio.

---

## ⚙️ Funcionalidades principales

- Gestión de usuarios (compradores y vendedores)
- Administración de eventos y categorías
- Gestión de funciones (Performance)
- Control de sectores y disponibilidad de asientos
- Venta de entradas con validaciones
- Generación automática de tickets en PDF
- Reportes por fecha y por categoría
- Actualización masiva de precios por sector

---

## 🧠 Aspectos Técnicos Implementados

- Modelado de base de datos relacional mediante transacciones
- Definición de reglas de negocio y eventos
- Uso de Business Components
- Implementación de Data Providers
- Procedimientos con estructuras For Each
- Consultas filtradas por fecha y categoría
- Generación de archivos PDF desde procedimiento
- Manejo de colecciones y lógica condicional
- Índices de usuario optimizados

---

## 🗂️ Modelo de Datos

Incluye entidades como:

- Country
- Customer
- Show
- ShowCategory
- Performance
- Sector
- Ticket
- Sale
- Products (Snack, Drink, Souvenir)

Se implementaron relaciones entre entidades y subtipos para estructurar correctamente la información.

---

## 📊 Procedimientos Implementados

- PerformanceByDate
- PerformanceGroupByType
- CountPerformance
- PrintTicket (con salida PDF)
- UpdatePrice
- IncreasePrice
- ViewSectors

---

## 🛠️ Tecnologías utilizadas

- GeneXus 18
- Base de datos relacional
- SQL
- Business Components
- Data Providers

---

## 📁 Contenido del repositorio

El repositorio incluye el archivo `.xpz` exportado desde GeneXus, que contiene la Knowledge Base completa del sistema.

---

## 📌 Contexto académico

Proyecto realizado como requisito obligatorio del Taller GeneXus.
