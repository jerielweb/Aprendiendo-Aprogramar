# 🟦 TypeScript: De Básico a Escalar

Esta carpeta contiene material de aprendizaje y ejercicios de código para dominar **TypeScript (TS)**, organizado en una ruta de progresión que va desde los fundamentos del tipado hasta conceptos avanzados de programación orientada a objetos (POO) y patrones de diseño.

## 🌟 Objetivo Principal

Proporcionar una ruta clara para que los desarrolladores de JavaScript puedan adoptar el tipado estático, mejorando la calidad del código, la mantenibilidad y la escalabilidad de sus proyectos.

---

## 📚 Estructura de Contenido por Niveles

El material está dividido en tres niveles de dificultad para guiar tu aprendizaje de forma progresiva.

| Carpeta | Nivel | Enfoque | Conceptos Clave |
| :--- | :--- | :--- | :--- |
| **01-Nivel-Basico/** | **Básico** | Fundamentos del Tipado | Tipos primitivos (`string`, `number`, `boolean`), `any`, `void`, Tipado de Funciones. |
| **02-Nivel-Intermedio/** | **Intermedio** | Estructuras de Datos y Modelado | Arrays, Tuplas, Enums, Uso de `Interfaces` y `Types` para objetos, Tipos de Unión e Intersección. |
| **03-Nivel-Avanzado/** | **Avanzado** | Patrones y Escalabilidad | Clases y POO (Herencia, Modificadores), Tipos Genéricos (`Generics`), Tipos de Utilidad (ej. `Partial`, `Readonly`), Módulos. |
| **04-Ejercicios-Retos/** | **Práctica** | Aplicación General | Problemas prácticos con soluciones para aplicar los conceptos aprendidos en los tres niveles. |

---

## 🛠️ Requisitos e Instalación

Para trabajar con los archivos `.ts` de esta carpeta, solo necesitas tener un entorno de Node.js configurado.

### Instalación de TypeScript

1. Asegúrate de tener **Node.js** instalado.
2. Instala TypeScript de forma global para usar el compilador (`tsc`):

    ```bash
    npm install -g typescript
    ```

### Compilación y Ejecución

Para ejecutar los archivos, puedes transpilarlos a JavaScript con `tsc` o usar `ts-node` para una ejecución directa:

```bash
# 1. Compilar (crea un .js)
tsc archivo.ts

# 2. Ejecutar (con Node el archivo .js)
node archivo.js

# Opcional: Ejecutar directo con ts-node (si lo instalaste)
ts-node archivo.ts
