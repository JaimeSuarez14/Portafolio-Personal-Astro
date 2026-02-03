---
title: 'Gestor Tareas 1'
subtitle: 'App Web'
description: 'Este un proyecto personal dividido en dos capas: el frontend que tiene la UI de gestión de tareas construida con React, Vite y TypeScript. y el Backend en Node.js con Express'
utils: [ 'Vite', 'React',"Typescript" ,'Tailwind', "Node"]
heroImage: '/images/GestorTareasV1React/lista.png'
pubDate: 'Jan 01 2026'
deployed: false
url: ''
urlGithub: 'https://github.com/JaimeSuarez14/app-gestion-tareas-react-frontend.git'
---

# Tienda Online Data Max
#### Plataforma de Venta en Línea
<div className="grid grid-cols-2 md:grid-cols-4 md:gap-1">
<img className="m-0" src="https://img.shields.io/badge/tailwind-E34F26?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="tailwind">
<img className="m-0"  src="https://img.shields.io/badge/react-58c4dc?style=for-the-badge&logo=react&logoColor=white" alt="react">
<img className="m-0"  src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
<img className="m-0"  src="https://img.shields.io/badge/typescript-1572B6?style=for-the-badge&logo=typescript&logoColor=white" alt="typescript">
</div>
Este un proyecto personal dividido en dos capas: el frontend que tiene la UI de gestión de tareas construida con React, Vite y TypeScript. y el Backend en Node.js con Express.



## Funcionalidades Principales

- Crear un usuario y hacer el login.
- Agregar un tarea y modificar las tareas.
- Modificar las tareas y eliminar las tareas.
- Agregar imagen a la tareas.
- Gestionar a los usuarios con admin.

<div className="grid grid-cols-1 md:grid-cols-2 md:gap-4">
  <div className="flex flex-col ">
   <div class="flex flex-col text-center">
    <img src="/images/GestorTareasV1React/lista.png" alt="Panadería Astro 1" className="w-full mx-auto object-cover shadow-lg hover:scale-105 transform transition-all  p-1 rounded-lg"/>
    <span class="-mt-7 dark:text-paragraph-dark text-paragraph-light">Lista de Tareas</span>
   </div>
   <div class="flex flex-col text-center">
     <img src="/images/GestorTareasV1React/PanelTareas.png" alt="Panadería Astro 2" className=" w-full h-full object-cover shadow-lg hover:scale-105 transform transition-all  p-1 rounded-lg"/>
     <span class="-mt-7 dark:text-paragraph-dark text-paragraph-light">Principal Tareas</span>
  </div>
  </div>
  <div className="flex flex-col overflow-hidden min-h-full mx-auto
  ">
    <img src="/images/GestorTareasV1React/movil.png" alt="Panadería Astro 3" className=" flex hover:scale-105 transform transition-all  flex-col items-center rounded-lg justify-center my-auto object-cover p-1 shadow-lg"/>
    <span class="-mt-7 text-nowrap text-center dark:text-paragraph-dark text-paragraph-light">Responsive Movil</span>
  </div>
</div>

## Tecnologías Utilizadas

La plataforma **Gestor de Tareas** está construida utilizando un conjunto de tecnologías modernas que aseguran una experiencia de usuario fluida y un rendimiento óptimo:

- React: Biblioteca para construir interfaces de usuario.
- Vite: Herramienta de construcción rápida para desarrollo web moderno.
- TypeScript: Superset de JavaScript que añade tipado estático.
- React Router: Para el enrutamiento en la aplicación.
- Redux Toolkit: Para la gestión del estado de la aplicación.
- Axios: Para realizar peticiones HTTP al backend.
- Tailwind CSS: Framework de CSS para un diseño rápido y personalizado.
- Node.js: Del lado del servidor para gestionar las apis
- cloudinary: Para gestionar las imagenes en la nube.

## 🔧 Instalación y Ejecución

Para ejecutar este proyecto localmente, necesitarás tener <a href="https://nodejs.org/" className="dark:text-white text-black" >Node.js</a> y npm instalados.

1.  Clona el repositorio:
    ```bash
    git clone https://github.com/JaimeSuarez14/app-gestion-tareas-react-frontend.git
    ```

2.  Navega al directorio del proyecto:
    ```bash
    cd app-gestion-tareas-react-frontend
    ```

3.  Instala las dependencias de desarrollo:
    ```bash
    npm install
    ```

4.  Inicia el servidor de desarrollo:
    ```bash
    npm start
    ```

Esto abrirá el proyecto en tu navegador web predeterminado.

---

## 📝 Uso
- Usuario Demo: jaime
- Password: 123456

1. Autenticación de usuarios: Registro e inicio de sesión.
2. Gestión de tareas: Crear, listar, ver detalles de tareas.
3. Panel de control: Visualización principal de las tareas.
4. Rutas protegidas: Solo los usuarios autenticados pueden acceder al panel de control.
