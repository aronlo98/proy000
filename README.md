# ♻️ EcoSwap: Plataforma de Intercambio Sustentable

EcoSwap es una aplicación web diseñada para fomentar la economía circular, permitiendo a los usuarios intercambiar artículos de segunda mano de manera sencilla y segura.

Este proyecto sirve como base académica para aprender el flujo de trabajo profesional en GitHub.

---

## 📋 Tabla de Features para GitHub Projects

Usa esta tabla para cargar tus **Issues** en el Project board. Cada fila representa una tarea que debe ser movida a través de las columnas (Todo, In Progress, Done).

| Título de la Issue | Descripción / Criterios de Aceptación | Labels | Milestone |
| :--- | :--- | :--- | :--- |
| **Setup: Estructura base** | Crear carpetas frontend/backend y archivo .gitignore. | `setup` | v1.0 - MVP |
| **Setup: Base de Datos** | Configurar el esquema inicial de tablas en PostgreSQL. | `backend` | v1.0 - MVP |
| **Auth: Registro de Usuarios** | Crear el formulario de registro con validación de email. | `frontend` | v1.0 - MVP |
| **Auth: Login con JWT** | Implementar autenticación segura en el servidor. | `backend` | v1.0 - MVP |
| **Catalog: Subir Producto** | Formulario para cargar nombre, foto y categoría. | `frontend` | v1.0 - MVP |
| **Catalog: Feed Principal** | Mostrar lista de productos disponibles en tarjetas. | `frontend` | v1.0 - MVP |
| **Interaction: Botón Interés** | Notificar al dueño cuando alguien quiere su producto. | `logic` | v1.1 - Beta |
| **Chat: Mensajería Básica** | Interfaz simple para coordinar el intercambio. | `frontend` | v1.1 - Beta |
| **Fix: Imágenes Estiradas** | Corregir CSS para que las fotos no pierdan proporción. | `bug` | v1.2 - Release |
| **Docs: Documentación API** | Redactar guía de uso de los endpoints (Swagger). | `docs` | v1.2 - Release |

---

## 🚀 Listado Detallado de Features

### 🔐 1. Gestión de Usuarios y Seguridad
* **Registro e Inicio de Sesión:** Sistema de autenticación seguro mediante JWT.
* **Perfiles Personalizados:** Gestión de información y fotos de perfil.

### 📦 2. Catálogo y Gestión de Productos
* **Publicación de Artículos:** Formulario dinámico para fotos y descripción.
* **Buscador Inteligente:** Filtros por categoría (Ropa, Electrónica, Hogar).

### 🤝 3. Sistema de Intercambio (Core)
* **Botón "Me Interesa":** Notificaciones al dueño del producto.
* **Chat Interno:** Mensajería integrada para coordinación.

---

## 📅 Hoja de Ruta (Milestones)

| Hito | Objetivo |
| :--- | :--- |
| **v1.0 - MVP** | Autenticación básica y listado de productos. |
| **v1.1 - Beta** | Sistema de chat y notificaciones de interés. |
| **v1.2 - Release** | Pulido de UI, corrección de bugs y despliegue. |

---

## 💻 Tech Stack
* **Frontend:** React / Next.js
* **Backend:** Node.js / Express
* **DB:** PostgreSQL
* **Infra:** Docker

---

## 👥 Instrucciones para Estudiantes
1. Selecciona una fila de la **Tabla de Features**.
2. Crea una **Issue** en el repositorio con ese título y descripción.
3. Asígnale el **Milestone** correspondiente.
4. Mueve la tarjeta en el **Project Board** según tu progreso.
