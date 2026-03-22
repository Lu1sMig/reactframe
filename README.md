# React 17: Design Patterns and Best Practices 🚀

Este repositorio contiene el seguimiento práctico, ejercicios y patrones de diseño aprendidos a través del libro **"React 17 Design Patterns and Best Practices"** de Carlos Santana Roldán. El objetivo es dominar la creación de interfaces de usuario robustas, escalables y mantenibles.

## 🛠️ Entorno de Desarrollo

Para este proyecto se ha configurado el siguiente entorno (basado en las recomendaciones del autor):

- **Editor:** Visual Studio Code
- **Node.js:** v23.10.0
- **Gestor de paquetes:** npm 10.9.2
- **Lenguaje Principal:** TypeScript (Template: `cra-template-typescript`)
- **Herramientas de Calidad:** ESLint y Prettier.

## 📖 Objetivos del Proyecto

El desarrollo de este repositorio se divide en los pilares fundamentales descritos en el libro:

1.  **Fundamentos de React:** Entender el funcionamiento de componentes y ciclo de vida.
2.  **JSX y Transpilación:** Usar Babel para sintaxis moderna a código compatible.
3.  **Patrones de Diseño:** Implementación de *Higher-Order Components (HOC)*, *Render Props* y *Compound Components*.
4.  **Hooks Avanzados:** Creación de hooks personalizados para lógica reutilizable.
5.  **Gestión de Estado:** Manejo de estado local, Context API y Redux.
6.  **Estilizado:** Implementación de componentes con `styled-components`.
7.  **Testing:** Pruebas unitarias y de integración con Jest y React Testing Library.

## 🚀 Cómo iniciar el proyecto

Si deseas replicar este entorno en tu máquina local:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Lu1sMig/reactframe.git

2. **Instalar Dependecias:**
    ```Bash
    npm install

Ejecutar en modo desarrollo:
   ```Bash
   npm start
   La aplicación se abrirá en http://localhost:3000.

## 🗂️ Estructura del Repositorio
```Bash  
/src/components: Componentes reutilizables siguiendo patrones atómicos.
/src/hooks: Lógica extraída en Custom Hooks.
/src/patterns: Ejemplos específicos de cada patrón del libro.
/src/styles: Configuraciones globales de CSS-in-JS.

Notas: Este proyecto se actualiza conforme avanzo en los capítulos del libro.

---
### Pasos para subirlo a GitHub:

1. **Inicializa Git** en la carpeta de tu proyecto (si no lo has hecho):
   ```bash
   git init
Crea el archivo README.md y pega el contenido anterior.

Agrega los archivos y haz tu primer commit:
    ```Bash
    git add .
    git commit -m "Initial commit: Setup de entorno y README"
Crea un repo en GitHub y vinculalo:

    ```Bash
    git remote add origin https://github.com/Lu1sMig/reactframe.git
    git branch -M main
    git push -u origin main

Consejo: Como tienes una versión de Node muy nueva (v23), si al ejecutar npm start te da algún error de compatibilidad con create-react-app, intenta usar:
npx create-react-app mi-proyecto --template typescript directamente.
