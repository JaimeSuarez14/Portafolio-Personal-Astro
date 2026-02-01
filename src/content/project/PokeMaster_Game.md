---

title: 'PokeMaster Games'
subtitle: 'Plataforma Web de mini-juegos '
description: 'Este es un proyecto web interactivo llamado "PokeDiversion" construido con React y TypeScript. Se trata de una plataforma de mini-juegos con temática Pokémon diseñada como proyecto educativo para aprender desarrollo web moderno.'
utils: [ 'Vite', 'React',"Tailwind" ,'Typescript']
heroImage: '/images/PokeMaster_Game/escritorio-inicio.png'
pubDate: 'Julio 31 2025'
deployed: true
url: 'https://adivina-el-pokemon-jaime.netlify.app/'
urlGithub: 'https://github.com/JaimeSuarez14/PokeMaster_Games.git'

---

# App Web PokeMaster Games
#### Plataforma Web de mini-juegos 
<div className="grid grid-cols-2 md:grid-cols-4 md:gap-1">
<img className="m-0" src="https://img.shields.io/badge/vite-E34F26?style=for-the-badge&logo=vite&logoColor=white" alt="vite">
<img className="m-0"  src="https://img.shields.io/badge/react-1572B6?style=for-the-badge&logo=react&logoColor=white" alt="react">
<img className="m-0"  src="https://img.shields.io/badge/tailwind-43853D?style=for-the-badge&logo=tailwind&logoColor=white" alt="tailwind">
<img className="m-0"  src="https://img.shields.io/badge/typescript-674ea7?style=for-the-badge&logo=typescript&logoColor=white" alt="typescript">
</div>

Este es un proyecto web interactivo llamado "PokeDiversion" construido con React y TypeScript. Se trata de una plataforma de mini-juegos con temática Pokémon diseñada como proyecto educativo para aprender desarrollo web moderno.

Es una Single Page Application (SPA) que combina:

- Un sistema de autenticación básico (login)
- Un dashboard de navegación
- Dos juegos interactivos

## Funcionalidades Principales

1. Juego "Adivina el Pokémon": Los usuarios ven una silueta de un Pokémon y deben adivinar su nombre. Incluye estadísticas de victorias/derrotas y animaciones de confeti al acertar.

2. Juego Tic Tac Toe (Tres en Raya): El clásico juego de estrategia con historial de movimientos y detección de ganador.

3. Sistema de Login: Autenticación básica para acceder a los juegos.

<div className="grid grid-cols-1 md:grid-cols-2 md:gap-4">
  <div className="flex flex-col ">
   <div class="flex flex-col text-center">
    <img src='/images/PokeMaster_Game/escritorio-inicio.png' alt="Panadería Astro 1" className="w-full mx-auto object-cover shadow-lg hover:scale-105 transform transition-all  p-1 rounded-lg"/>
    <span class="-mt-7 dark:text-paragraph-dark text-paragraph-light">Home Principal</span>
   </div>
    <div class="flex flex-col text-center"> 
     <img src='/images/PokeMaster_Game/primerjuego.png' alt="Panadería Astro 2" className=" w-full h-full object-cover shadow-lg hover:scale-105 transform transition-all  p-1 rounded-lg"/>
     <span class="-mt-7 dark:text-paragraph-dark text-paragraph-light">Tic Tac Toe</span>
    </div>
  </div>
  <div className="flex flex-col overflow-hidden min-h-full mx-auto
  "> 
    <img src='/images/PokeMaster_Game/pokeGame.png' alt="Panadería Astro 3" className=" flex hover:scale-105 transform transition-all  flex-col items-center rounded-lg justify-center my-auto object-cover p-1 shadow-lg"/>
    <span class="-mt-7 text-nowrap text-center dark:text-paragraph-dark text-paragraph-light">Responsive Movil</span>
  </div>
</div>

## Stack Tecnológico
- React 19 + TypeScript
- Vite (bundler)
- Tailwind CSS (estilos)
- React Router (navegación)
- PokéAPI (datos de Pokémon)


## 🔧 Instalación y Ejecución

Para ejecutar este proyecto localmente, necesitarás tener <a href="https://nodejs.org/" className="dark:text-white text-black" >Node.js</a> y npm instalados.

1.  Clona el repositorio:
    ```bash
    git clone https://github.com/JaimeSuarez14/PokeMaster_Games.git
    ```

2.  Navega al directorio del proyecto:
    ```bash
    cd PokeMaster_Games

    ```

3.  Instala las dependencias de desarrollo:
    ```bash
    npm install
    ```

4.  Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```

Esto abrirá el proyecto en tu navegador web predeterminado.

---

## 📝 Uso

Los datos del demo son:
- Usuario: jaime
- Password: admin

1. Inicia sesión con tu usuario y contraseña para acceder a las funcionalidades.
2. En el dashboard elije el juego.
3. Juego "Adivina el Pokémon": Los usuarios ven una silueta de un Pokémon y deben adivinar su nombre. Incluye estadísticas de victorias/derrotas y animaciones de confeti al acertar.
4. Juego Tic Tac Toe (Tres en Raya): El clásico juego de estrategia con historial de movimientos y detección de ganador.

Esta pagina transmite los siguiente: 
Son facil de usar, Transmiten diversión y juegos múltiples, Son cortos y funcionan bien como URL del Api
Tienen potencial para expandirse con más juegos en el futuro.