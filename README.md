# 📘 Unidad 3 – Web Services  
**Curso:** SI730 – Aplicaciones Web  
**Universidad:** Universidad Peruana de Ciencias Aplicadas (UPC)  
**Nivel:** Pregrado  

---

## 📌 Introducción

Este repositorio contiene las **diapositivas correspondientes a la Unidad 3** del curso **Aplicaciones Web (SI730)**.  
La Unidad 3 está enfocada en el **desarrollo de aplicaciones del lado servidor**, específicamente en la construcción de **Web Services RESTful** utilizando **ASP.NET Core**, **Entity Framework Core** y el ecosistema **.NET**.

En esta unidad se abordan aspectos clave como **persistencia de datos**, **configuración del modelo**, **transacciones**, **seguridad**, **internacionalización** y **deployment**, aplicando una **Arquitectura Orientada a Servicios (SOA)** y buenas prácticas de ingeniería de software.

---

## 🎯 Objetivo de la Unidad

Al finalizar esta unidad, el estudiante será capaz de:

- Implementar **Web Services RESTful** con ASP.NET Core.
- Diseñar y configurar la **capa de persistencia** usando Entity Framework Core.
- Aplicar **Data Annotations y Fluent API** para el modelado de datos.
- Realizar operaciones CRUD con control de **transacciones**.
- Implementar **validaciones y controladores** en ASP.NET Core MVC.
- Aplicar **internacionalización (i18n)** en Web Services.
- Implementar **seguridad** en APIs mediante JWT y CORS.
- Desplegar aplicaciones backend en plataformas cloud.

---

## 📂 Contenido del Repositorio

Todos los archivos listados pertenecen a la **Unidad 3 – Web Services**:

---

### 1️⃣ Entity Framework Core – Data Annotations & Fluent API
- Introducción a **Entity Framework Core** como ORM.
- Configuración del modelo mediante:
  - Convenciones
  - Data Annotations
  - Fluent API
- Definición de claves primarias, relaciones e índices.
- Comparación entre Data Annotations y Fluent API.

---

### 2️⃣ ASP.NET Core & Web Services – Review
- Repaso de **ASP.NET Core MVC**.
- Patrón MVC y middleware pipeline.
- Inyección de dependencias (DI).
- Principios RESTful.
- Uso de HTTP verbs y JSON.
- Versionamiento de APIs.
- Modelo de madurez de Richardson y HATEOAS.

---

### 3️⃣ Entity Framework Core – Queries, Controllers & Validations
- Consultas con **LINQ**.
- Carga de datos relacionados (`Include`, `ThenInclude`).
- Uso de consultas SQL sin formato.
- Implementación de **controladores**.
- Validaciones con **Data Annotations**.
- Manejo de errores y ModelState.

---

### 4️⃣ Saving Data, Transactions & Inheritance
- Uso de `DbContext` como Unit of Work.
- Operaciones CRUD:
  - Insert
  - Update
  - Delete
- Manejo de relaciones entre entidades.
- Control de transacciones:
  - `BeginTransaction`
  - Commit y Rollback
- Mapeo de herencia:
  - Table-Per-Hierarchy (TPH)
  - Table-Per-Type (TPT)

---

### 5️⃣ Web Services Internationalization
- Conceptos de **globalization y localization**.
- Configuración de `RequestLocalizationMiddleware`.
- Uso de archivos `.resx`.
- Localización de mensajes y errores.
- Internacionalización de:
  - Strings
  - Data Annotations
  - Model Binding

---

### 6️⃣ Web Services Deployment
- Deployment de Web APIs en **Azure**.
- Publicación desde Visual Studio y Rider.
- Uso de **Azure App Service**.
- Integración de **MySQL In App**.
- Otras opciones de hosting para ASP.NET Core.

---

### 7️⃣ Web Services Security
- Introducción a **JSON Web Tokens (JWT)**.
- Estructura y uso de JWT:
  - Header
  - Payload
  - Signature
- Autenticación y autorización con JWT.
- Configuración de **CORS**.
- Integración de seguridad en ASP.NET Core.

---

## 🧠 Importancia de la Unidad

La Unidad 3 consolida el desarrollo **backend profesional**, permitiendo al estudiante:

- Construir APIs RESTful completas y escalables.
- Gestionar datos de forma segura y transaccional.
- Aplicar seguridad y control de acceso.
- Preparar aplicaciones para entornos productivos.
- Integrar correctamente frontend y backend.

Esta unidad es clave para el desarrollo de **aplicaciones web empresariales** y proyectos finales del curso.

---

## 📚 Uso del Repositorio

Este repositorio tiene un **propósito académico** y sirve como:

- Material de estudio del curso SI730.
- Referencia para el desarrollo de Web Services en .NET.
- Apoyo para proyectos backend con ASP.NET Core y EF Core.

---
