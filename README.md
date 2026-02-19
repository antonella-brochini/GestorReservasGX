# Gestor de Reservas Online – Sistema de Venta de Entradas
Proyecto Académico – Taller GeneXus  
Universidad ORT Uruguay

---

## 📌 Descripción General

Sistema web desarrollado en GeneXus 18 para la gestión integral de venta de entradas para espectáculos (conciertos, obras de teatro, deportes, etc.).

La aplicación permite administrar eventos, funciones, sectores, disponibilidad de asientos, precios y ventas, garantizando integridad de datos mediante reglas de negocio y lógica transaccional.

---

## 🏗️ Arquitectura y Modelo de Datos

El sistema fue diseñado utilizando modelado relacional mediante transacciones GeneXus, contemplando:

### Entidades principales:
- Country
- Customer
- Show
- ShowCategory
- Performance
- Sector
- Ticket
- Sale
- Products (Snack, Drink, Souvenir)
- Place

### Características del modelo:
- Relaciones entre entidades con claves foráneas
- Uso de subtipos para estructuración jerárquica
- Índices de usuario para optimización de consultas
- Transacciones dinámicas
- Business Components para manipulación programática

---

## ⚙️ Funcionalidades Implementadas

### Gestión de Usuarios
- Registro de compradores
- Asociación con país

### Gestión de Eventos
- Catálogo de espectáculos
- Clasificación por categoría
- Asociación con lugar y fecha

### Gestión de Funciones (Performance)
- Control de capacidad por sector
- Manejo de precios
- Validaciones de disponibilidad

### Venta de Entradas
- Selección de sector
- Control de cantidad
- Registro de cliente
- Generación de ticket

### Generación de PDF
- Procedimiento PrintTicket
- Salida en formato PDF
- Datos dinámicos por TicketId

---

## 🔎 Procedimientos y Lógica de Negocio

### Consultas y Reportes
- PerformanceByDate
- PerformanceGroupByType
- CountPerformance

### Gestión de Precios
- UpdatePrice
- IncreasePrice
- Aplicación de porcentaje sobre sectores seleccionados

### Manejo de Colecciones
- Uso de colecciones en eventos
- Lógica condicional sobre selección múltiple

### Business Components
- Creación, actualización y eliminación programática
- Manejo de mensajes de error

---

## 🧠 Conceptos Técnicos Aplicados

- Modelado relacional normalizado
- Uso de For Each con filtros
- Validaciones mediante reglas
- Manejo de eventos (Insert, Update, Delete)
- Parámetros de entrada en procedimientos
- Generación de archivos externos (PDF)
- Separación entre capa transaccional y lógica procedimental
- Optimización mediante índices

---

## 🛠️ Tecnologías

- GeneXus 18
- Base de datos relacional
- SQL
- Business Components
- Data Providers
- Web Panels personalizados

---

## 📂 Contenido del Repositorio

El repositorio incluye el archivo `.xpz` que contiene la Knowledge Base completa exportada desde GeneXus.

---

## 👩‍💻 Contexto Académico

Proyecto desarrollado como requisito obligatorio del Taller GeneXus de la carrera Analista en Tecnologías de la Información.

