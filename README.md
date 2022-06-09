# Leonel Valentini  - Curriculum Vitae

Este proyecto ademas de mantener mi CV actualizado, lo comparto a la comunidad ya que es una forma facil de tenerlo online y ademas actualizarlo.

Mi CV: [http://leonelvalentini.github.io/digital-cv/tree/main/dist/index.html](http://leonelvalentini.github.io/digital-cv/tree/main/dist/index.html).

## ¿Qué puede hacer el proyecto?

* Ayuda a manejar tu CV como una WebAPP (HTML + CSS + JS).
* Se genera automaticamente y publica como HTML y PDF, haciendo un push al `master`.

## Instalación

1. Clonar el repositorio
1. Instalar dependencias `npm install`.
1. Ejecutar `npm run deploy` para inicializar `gh-pages`. Solo la primera vez, luego hacer push al `master`.

## Uso

1. Localmente `npm start`.
1. Actualizar el contenido en `src`.

### Update contents

El proyecto usa [HandlebarsJS](https://github.com/wycats/handlebars.js/) como template.

El HTML principal se encuentra en [src/templates/index.html](src/templates/index.html). 
La información a editar se encuentra en [src/metadata/metadata.js](src/metadata/metadata.js).