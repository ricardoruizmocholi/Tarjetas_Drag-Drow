# Tarjetas_Drag-Drow

#  Plantillas - Dashboard Fullstack de Gestión Visual

**Plantillas** es una aplicación web tipo SaaS diseñada para la organización personal y profesional mediante tableros dinámicos. Permite gestionar múltiples espacios de trabajo, personalizar tarjetas y organizar prioridades de forma intuitiva.

![Licencia](https://img.shields.io/badge/license-MIT-blue)
![Stack](https://img.shields.io/badge/stack-PHP%20%7C%20JS%20%7C%20SQLite-orange)

##  Características Principales

* **Gestión Multitablero:** Crea, renombra y elimina diferentes tableros para separar proyectos o temáticas.
* **Interfaz Interactiva Drag & Drop:** Reordena tus tarjetas de forma nativa mediante arrastrar y soltar.
* **Personalización Avanzada:** Controla el tamaño (filas y columnas) y el color de fondo de cada tarjeta para una jerarquía visual clara.
* **Persistencia de Datos:** Almacenamiento seguro de cada cambio en tiempo real vinculado a tu cuenta de usuario.
* **Diseño Moderno:** Interfaz basada en *Glassmorphism* con efectos de desenfoque y gradientes.

## Stack Tecnológico

### Frontend
* **HTML5 & CSS3:** Uso de Custom Properties (Variables CSS) y Flexbox/Grid para un diseño responsivo y moderno.
* **Vanilla JavaScript:** Lógica de manipulación del DOM, gestión de estados y API Fetch sin dependencias externas.

### Backend & Seguridad
* **PHP:** Procesamiento de la API para acciones de CRUD (Create, Read, Update, Delete).
* **SQLite:** Base de Datos ligera y eficiente que no requiere un servidor complejo.
* **Autenticación Segura:** Implementación de `password_hash` para el cifrado de credenciales y validación de sesiones.

## Estructura del Proyecto

* `api.php`: Punto de entrada único para la gestión de usuarios, carga y guardado de datos.
* `index.html`: Aplicación Single Page (SPA) que contiene la interfaz y la lógica del cliente.
* `tarjetitas.db`: Base de datos SQLite (generada automáticamente al iniciar).

##  Instalación y Uso

1.  Clona el repositorio en tu servidor local (XAMPP, Laragon, Apache).
2.  Asegúrate de que el servidor tenga habilitada la extensión `pdo_sqlite`.
3.  Accede a `platilla2.html` desde tu navegador.
4.  ¡Regístrate y comienza a organizar tus ideas!

---
Desarrollado para optimizar flujos de trabajo personales.
