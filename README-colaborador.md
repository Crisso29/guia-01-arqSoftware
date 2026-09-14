# 🏥 Sistema de Gestión de Citas de Salud (`arq-citas-salud`)

> **Asignatura:** Arquitectura de Software [IS-488]  
> **Semestre:** 2026-II  
> **Docente:** Ing. Lizbeth Jaico Quispe  
> **Institución:** Universidad Nacional de San Cristóbal de Huamanga (UNSCH)  
> **Escuela Profesional:** Ingeniería de Sistemas  

---

## 📌 1. Información del Estudiante / Lider de Proyecto

| Campo | Detalle |
| :--- | :--- |
| **Nombre Completo:** | Juan Josue Huaman Soto |
| **Código Estudiantil:** | [Tu Código, ej: 27210139] |
| **Correo Institucional:** | `juan.huaman.27@unsch.edu.pe` |
| **Usuario GitHub:** | [@juanjo166](https://github.com/juanjo166) |
| **Rol en el Proyecto:** | Lead Architecture / Developer |

---

## 🎯 2. Visión del Curso y Expectativas

### 📘 Descripción de la Asignatura
El curso de **Arquitectura de Software** aborda las decisiones estratégicas de alto nivel que estructuran un sistema, definiendo la interacción entre componentes, la separación de responsabilidades y la garantía de atributos de calidad como mantenibilidad, escalabilidad, seguridad y rendimiento.

### 💡 Expectativas Personales
* **Diseño Arquitectónico:** Comprender la transición desde los requerimientos de negocio hacia decisiones arquitectónicas fundamentadas en patrones y atributos de calidad.
* **Buenas Prácticas:** Dominar las convenciones profesionales en control de versiones (Git Flow, Conventional Commits, Pull Requests) y documentación viva mediante *Architecture Decision Records* (ADRs).
* **Construcción de Microservicios/Módulos:** Desarrollar sistemas desacoplados utilizando tecnologías modernas como Node.js, Express, Docker y pruebas automatizadas.

---

## 🛠️ 3. Verificación del Entorno de Desarrollo

El entorno local ha sido verificado y configurado con las siguientes especificaciones:

| Herramienta | Versión Requerida | Versión Instalada | Comando de Verificación |
| :--- | :---: | :---: | :--- |
| **Node.js** | `v20.x.x` | `v20.11.0` | `node --version` |
| **npm** | `10.x.x` | `10.2.4` | `npm --version` |
| **Git** | `v2.4x.x`+ | `v2.55.0` | `git --version` |
| **VS Code** | Última versión | Instalado | `code --version` |


### 📸 Evidencia de Configuración
![Verificación del Entorno](./docs/paso1.png)

---

## 📁 4. Estructura del Proyecto

El proyecto sigue una organización modular diseñada para separar la documentación de la implementación desde el primer día[cite: 1]:

```text
arq-citas-salud/
├── docs/                      # Documentación del sistema
│   ├── 00-caso-de-estudio.md  # Especificación del caso de negocio
│   └── decisiones/            # Registros de Decisiones Arquitectónicas (ADRs)
│       └── ADR-000-plantilla.md
├── src/                       # Código fuente de la aplicación
│   ├── app.js                 # Configuración de Express y Middlewares
│   └── server.js              # Punto de entrada del servidor HTTP
├── tests/                     # Pruebas unitarias y de integración
├── .gitignore                 # Archivos e directorios excluidos de Git
├── package.json               # Dependencias y scripts de Node.js
└── README.md                  # Documentación principal del repositorio