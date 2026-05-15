# ♻️ EcoSwap: Plataforma de Intercambio Sustentable

EcoSwap es una aplicación web diseñada para fomentar la economía circular, permitiendo a los usuarios intercambiar artículos de segunda mano de manera sencilla y segura.

Este proyecto sirve como base académica para aprender el flujo de trabajo profesional en GitHub, incluyendo la gestión de **Issues**, **Milestones** y **Projects**.

---

## 🚀 Listado de Features Planificados

### 🔐 1. Gestión de Usuarios y Seguridad
* **Registro e Inicio de Sesión:** Sistema de autenticación seguro mediante JWT.
* **Perfiles Personalizados:** Cada usuario puede gestionar su información, foto de perfil y ver su historial de intercambios.
* **Validaciones de Seguridad:** Protección de rutas y validación de datos en el lado del servidor.

### 📦 2. Catálogo y Gestión de Productos
* **Publicación de Artículos:** Formulario dinámico para subir fotos (con previsualización), descripciones y estados del producto.
* **Exploración (Feed):** Muro principal con scroll infinito o paginación para ver los productos más recientes.
* **Buscador Inteligente:** Filtros avanzados por categoría (Ropa, Electrónica, Hogar) y búsqueda por palabras clave.

### 🤝 3. Sistema de Intercambio (Core)
* **Botón "Me Interesa":** Sistema de notificaciones en tiempo real al dueño del producto.
* **Chat Interno:** Mensajería integrada para coordinar puntos de encuentro y detalles del intercambio.
* **Confirmación de Match:** Flujo para marcar un intercambio como "Exitoso" y retirar el producto del catálogo.

### 🛠️ 4. Infraestructura y Calidad
* **Contenedores con Docker:** Configuración completa con `docker-compose` para base de datos y aplicación.
* **CI/CD con GitHub Actions:** Ejecución automatizada de pruebas unitarias en cada Pull Request.
* **Documentación de API:** Documentación interactiva de todos los endpoints disponibles.

---

## 📅 Hoja de Ruta (Milestones)

| Hito | Objetivo | Estado |
| :--- | :--- | :--- |
| **v1.0 - MVP** | Autenticación básica y listado de productos. | 🏗️ En desarrollo |
| **v1.1 - Beta** | Sistema de chat y notificaciones de interés. | ⏳ Pendiente |
| **v1.2 - Release** | Pulido de UI, corrección de bugs y despliegue final. | ⏳ Pendiente |

---

## 💻 Tech Stack Sugerido
* **Frontend:** React / Next.js
* **Backend:** Node.js (Express) o Python (FastAPI/Django)
* **Base de Datos:** PostgreSQL
* **DevOps:** Docker & GitHub Actions

---

## 👥 Contribución
Este es un proyecto educativo. Para contribuir:
1. Elige una **Issue** del Backlog.
2. Mueve la tarjeta a **In Progress** en el Project board.
3. Crea un Pull Request vinculando el número de la tarea (ej: `Closes #1`).
