# 🚀 JavaScript-web: El Lenguaje del Navegador

Esta carpeta está dedicada a la exploración y el dominio de **JavaScript (JS)**, el lenguaje fundamental de la web. Aquí aprenderás la lógica del lenguaje y cómo interactuar con el entorno del navegador para crear sitios web dinámicos.

## 🌟 Objetivo Principal

El objetivo es construir una **base sólida en la sintaxis de JavaScript, las funciones asíncronas, y la manipulación del DOM (Document Object Model)**, habilidades esenciales para cualquier desarrollador Frontend.

---

## 📚 Estructura de Contenido por Niveles

El material está dividido en tres niveles de dificultad para asegurar una progresión lógica, centrándose en el estándar **ES6+** (ECMAScript 2015 y posteriores).

| Carpeta | Nivel | Enfoque | Conceptos Clave |
| :--- | :--- | :--- | :--- |
| **01-Nivel-Basico/** | **Básico** | Fundamentos y Sintaxis | Variables (`let`, `const`), Tipos de Datos, Estructuras de Control (`if/else`, `switch`), Bucles, Funciones básicas. |
| **02-Nivel-Intermedio/** | **Intermedio** | Lógica Funcional y DOM | Arrays, Objetos, *Destructuring*, *Spread/Rest Operators*, Funciones de Flecha, Introducción al **DOM** (Selección de elementos). |
| **03-Nivel-Avanzado/** | **Avanzado** | Asincronía y POO | **Asincronía** (`Promises`, `async/await`), Peticiones HTTP (`fetch`), Clases y Herencia (POO), Manejo de Eventos en el DOM. |
| **04-Ejercicios-Retos/** | **Práctica** | Aplicación Web | Retos centrados en manipular el DOM, manejar *timers* y consumir APIs sencillas. |

---

## 🛠️ Requisitos para Ejecutar el Código

La gran ventaja de JavaScript es que su código puede ejecutarse en dos entornos principales sin instalación adicional (solo necesitas un navegador y Node.js si quieres ejecutarlo fuera del navegador):

### Entornos de Ejecución

1.  **Navegador Web:** Ideal para los archivos que manipulan el **DOM** (archivos Intermedios y Avanzados). Simplemente abre el archivo HTML que referencia el script JS.
2.  **Node.js:** Perfecto para ejecutar archivos que solo se centran en la lógica pura (archivos Básicos y algunas tareas Avanzadas).

### Ejecución de Código con Node.js

Para ejecutar los archivos de lógica pura desde tu terminal:

```bash
# Navega a la carpeta deseada (ej. Básico)
cd 01-Nivel-Basico

# Ejecuta el archivo
node nombre_archivo.js
