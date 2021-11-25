<div align="center">
  <h1>Curso Avanzado de React</h1>
</div>

# ¿Qué es React?

Es un sistema de plantillas para gestionar las vistas que utiliza un lenguaje de marcado llamado JSX, similar a HTML.

## Caracteristicas básicas de react
* Está basado en componentes: Toda la UI se divide en elementos más pequeños llamados componentes, en react, todo es un componente.
* Es [declarativo](https://dev.to/itsjzt/declarative-programming--react-3bh2): expresa la lógica de un cálculo sin describir su flujo de control, es un estilo de programación en el que el que se define “qué” es la solución sin importar cómo se llegó a ella.

# Proyecto
En este curso se va a desarrollar una aplicación desde cero. El proyecto consiste en hacer un clon de la aplicación conocida como [Instagram](https://www.instagram.com/), las herramientas que vamos a ocupar son las siguientes: 
- React
- Webpack
- Babel
- style-components (libreria)
- Standard JS (Linter)
- GraphQL & React Apollo (Fetching de datos)
- Reach Router (Enrutado de la SPA)
- Lighthouse & Cypress (Buenas practicas)
- React Helmet (SEO)
- Workbox (PWA)
- Now (Deploy)

# Clonando el repositorio e instalando Webpack
Pasos para iniciar el proyecto:

- **Paso 1**: Vamos a clonar el repositorio desde github.com/midudev/curso-platzi-react-avanzado usando `git clone URL_DEL_REPO` en nuestra consola.
- **Paso 2**: Vamos a instalar webpack y webpack-cli como dependencias de desarrollo con: `npm i webpack wepack-cli --save-dev`.
- **Paso 3**: Crearemos una carpeta llama src y dentro de ella un archivo `index.js` en el cual colocaremos solo un console.log('Empezamos el curso!').
- **Paso 4**: Crearemos en el root de nuestro proyecto un archivo `webpack.config.js` el cual tendrá toda la configuración de webpack
- **Paso 5**: Instalaremos html-webpack-plugin con: `npm i html-webpack-plugin --save-dev`.
- **Paso 6**: Instalaremos webpack-dev-server con: `npm i webpack-dev-server --save-dev`.
- **Paso 7**: Añadiremos un nuevo script llamado dev en nuestro package.json: `"dev": "webpack serve"`.
