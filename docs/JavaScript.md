# JavaScript: Un Lenguaje Dinámico y Versátil

## 1. Historia del Lenguaje

JavaScript fue creado en 1995 por Brendan Eich, un ingeniero de Netscape, con el objetivo de hacer que las páginas web fueran interactivas. Esta idea surgió a partir de la "Guerra de los navegadores" que se esta librando entre Netscape y Internet Explorer, si no podían competir contra los recursos de un gigante como Microsoft competirían en originalidad.

- **Nombre Original**: Inicialmente se llamó Mocha, luego LiveScript y finalmente JavaScript por razones de marketing (para aprovechar la popularidad de Java).

- **Lanzamiento**: Netscape lanzó JavaScript 1.0 en 1995 con el navegador Netscape Navigator 2.0.

- **Estandarización**:

    - **1997**: Se define como ECMAScript (ES) bajo el estándar ECMA-262.

    - **2009**: ES5 introduce mejoras en compatibilidad y JSON.

    - **2015**: ES6 (ECMAScript 2015) trae let, const, clases, arrow functions y promesas.

    - **2023**: Las versiones modernas siguen evolucionando con nuevas features anuales.

**Documentación Consultada**: 
- [La historia completa de JavaScript, el único lenguaje que entienden los navegadores](https://ed.team/blog/la-historia-completa-de-javascript-el-unico-lenguaje-que-entienden-los-navegadores)
- [Qué es JavaScript](https://openwebinars.net/blog/que-es-javascript/)

## 2. Campo de Aplicación

JavaScript es el lenguaje más utilizado en la web y se aplica en:

- **Desarrollo Web (Frontend y Backend)**:

    - **React, Angular, Vue**: Frameworks para interfaces interactivas.

    - **Node.js**: Permite usar JavaScript en el backend (Ej: Netflix, PayPal, eBay).

- **Aplicaciones de Escritorio y Móviles**:

    - **Electron.js** (Slack, VS Code) para apps de escritorio.

    - **React Native, Ionic** para apps móviles multiplataforma.

- **Videojuegos**:

    - **Phaser.js, Three.js**: Desarrollo de juegos 2D y 3D en el navegador.

    - **Babylon.js**: Motor 3D para juegos y experiencias interactivas.

- **Machine Learning y Big Data**:

    - **TensorFlow.js**: Machine Learning en el navegador.

    - **D3.js**: Visualización de datos interactiva.

**Documentación Oficial MDN**: [Casos de Uso de JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)

## 3. Tipado de Variables y Paradigmas

- **Tipado Débil y Dinámico**: No es necesario declarar tipos (var a = 5; a = "Hola"; es válido).

- **Paradigmas**:

  - **Orientado a Objetos** (prototipos en lugar de clases tradicionales).

  - **Funcional** (first-class functions, closures, arrow functions).

  - **Asíncrono** (event loop, callbacks, promesas y async/await).

**Documentación Oficial**: [Guía de Tipado en JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript/Data_structures)

## 4. Curiosidades

### a) **JavaScript vs. Java**

- A pesar del nombre, JavaScript y Java no están relacionados. Fue una estrategía de mercado que usaron para aprovecharse de la fama de Java y potenciar JavaScript antes llamado LiveScript (porque eran scripts vivos en el navegador).

### b) **El NaN Más Extraño**

- NaN === NaN devuelve false en JavaScript.

### c) **JavaScript en el Espacio**

- NASA usa JavaScript para simulaciones y paneles de control.

### d) **El Motor de JavaScript Más Rápido**

- V8 (Google Chrome) es el más optimizado y se usa en Node.js.

### e) **JavaScript en Dispositivos IoT**

- Espruino y Johnny-Five permiten programar hardware con JavaScript.

### f) **La fatiga JavaScript**
- Este lenguaje se apoderó de casi todas las industrias del desarrollo de software durante la década del 2010 al 2020, incluso llegó a hablarse de la fatiga JavaScript. 

### g) **En tan solo una semana**
- Este lenguaje que llegó a dominar el mundo y es el único lenguaje en el desarrollo frontend (con el permiso de Web Assembly) fue creado en apenas una semana!

### h) **Solo uno puede sobrevivir... ah que aún están los dos**
-  JavaScript puso en guerra a dos empresas enormes y gracias a el se crearon Firefox y Google Chrome.


## 5. IDEs y Herramientas

- **Visual Studio Code** ([Sitio Oficial](https://code.visualstudio.com/)): El editor más popular para JavaScript.

- **WebStorm** ([Sitio Oficial]()https://www.jetbrains.com/webstorm/): IDE avanzado de JetBrains.

- **ESLint** ([Sitio Oficial](https://eslint.org/)): Herramienta para detectar errores en el código.

- **Parcel** ([Sitio Oficial](https://es.parceljs.org/)) y **Webpack** ([Sitio Oficial](https://webpack.js.org/)): Empaquetadores de módulos modernos.

## 6. Frameworks y Bibliotecas

- **React.js** ([Sitio Oficial](https://react.dev/)): Creado por Facebook, facilita la creación de interfaces.

- **Vue.js** ([Sitio Oficial](https://vuejs.org/)): Framework progresivo y fácil de aprender.

- **Angular** ([Sitio Oficial](https://angular.dev/)): Creado por Google, ideal para aplicaciones grandes.

- **Node.js** ([Sitio Oficial](https://nodejs.org/es)): Permite ejecutar JavaScript en servidores.

- **Express.js** ([Sitio Oficial](https://expressjs.com/)): Framework ligero para backend en Node.js.

## 7. Empresas e Instituciones Clave

- **Google**: Desarrolló el motor V8 y frameworks como Angular.

- **Meta (Facebook)**: Creador de React.js y React Native.

- **Mozilla**: Desarrollador del motor SpiderMonkey y Firefox.

**Documentación Oficial**: [JavaScript en Mozilla]()

## 8. Versiones y Estándares

Para poder estandarizar JavaScript Netscape envía su código de JavaScript (su especificación) a **ecma**, una organización europea que se encarga de hacer estándares de tecnologías. Para el año 1997, ecma lanzó la primera versión de su estándar, llamado ECMAScript 1.

- **ECMAScript 1 (1997)**:

- **ECMAScript 2 (1998)**:

- **ECMAScript 3 (1999)**: Soporte de expresiones regulares. Nuevas sentencias de control. Manejo de excepciones (bloque try-catch). Definición de errores más precisa. Formateo de salidas numéricas de datos. Manejo de strings más avanzado.

- **ECMAScript 4**: Nunca salió... y pasaron ¡10 años! hasta la siguiente. ([ECMAScript 4: The missing version](https://evertpot.com/ecmascript-4-the-missing-version/))

- **ECMAScript 5 (2009)**: JSON nativo, strict mode, nuevos métodos de arrays.

- **ECMAScript 6 (2015)**: let, const, clases, promesas, arrow functions.

- **ECMAScript 2017+**: async/await, optional chaining, nullish coalescing.

**Documentación Oficial**: [ECMAScript](https://tc39.es/ecma262/)

**Otra documentación consultada**: [La especificación ECMAScript](https://lenguajejs.com/javascript/introduccion/ecmascript/)

