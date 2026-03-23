# React 19.2: Design Patterns and Best Practices 🚀

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

2. **Verificar e instalar Dependecias:**
    ```bash
    node -v && npm -v && nvm --version && tsc -v

3. **Instalar dependencias**
    ```bash
    ⌂⌂ Navega al directorio de trabajo

    ⌂⌂ Install
    nvm install node o nvm use [versión]
    npm install -g create-react-app
    
    ⌂⌂ Crear el primer app y ejecuta:
    npx create-react-app mi-proyecto-react --template typescript
    
    ⌂⌂ Alterminar se debe ver: D:\app_react_\mi-proyecto-react
    ⌂⌂ Ejecuta el servidor
    npm start
    
    ⌂⌂La aplicación se abrirá en http://localhost:3000.

## 🗂️ Estructura del Repositorio
La arquitectura sigue una organización modular para facilitar el estudio de cada patrón:
    
   ```bash
   /
   ├── public/          + Archivos estáticos e index.html -(favicon/manifest/robots)
   ├── src/
   │   ├── components/  + Componentes reutilizables y atómicos
   │   ├── hooks/       + Custom Hooks para lógica extraída
   │   ├── patterns/    + Ejemplos específicos de cada capítulo del libro
   │   ├── views/       + Páginas principales o contenedores de alto nivel
   │   ├── App.tsx      + Punto de entrada de la aplicación
   │   └── index.tsx    + Renderizado raíz
   ├── package.json     + Scripts y dependencias
   └── tsconfig.json    + Configuración de TypeScript
   -- Notas: Este proyecto se actualiza conforme avanzo en los capítulos del libro.

## 🗂️ GitHub:
1. **Inicializa Git** en la carpeta de tu proyecto (si no lo has hecho):
   ```bash
   git init
    Crea el archivo README.md y registra comentario.
2. **Crea un repo en GitHub y vinculalo**
    ```Bash
    git remote add origin https://github.com/Lu1sMig/reactframe.git
    git branch -M main
    git commit "##"
    git push -u origin main
3. **Agregar Files a Git** por cambios en el equipo
    ```Bash
    git add .
    git commit -m "Initial commit: Setup de entorno y README"
    git push -u origin main
4. **Actualizar Files en Equipo** con cambios de GitHub-online
   ```bash
   git pull origin main
