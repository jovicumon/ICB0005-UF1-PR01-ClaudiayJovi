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
- [La historia completa de JavaScript, el único lenguaje que entienden los navegadores](https://ed.team/blog/la-historia-completa-de-javascript-el-unico-lenguaje-que-entienden-los-navegadores) (Leanlo que está muy chulo)
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

### Evolución de ECMAScript (ES) desde 1997 hasta 2025
**ECMAScript 1 (1997)**:
  - Primera versión del estándar basado en JavaScript de Netscape.
  - Introducción de las funciones básicas, operadores y estructuras de control.

**ECMAScript 2 (1998)**:
  - Pequeñas modificaciones y correcciones para alinearse con ISO/IEC 16262.

**ECMAScript 3 (1999)**:
  - Soporte de expresiones regulares.
  - Manejo de excepciones (try-catch).
  - Definición más precisa de errores.
  - Métodos avanzados para strings (trim, replace, match, etc.).
  - Formateo de salidas numéricas (toFixed, toExponential).

**ECMAScript 4 (Cancelado)**:
  - Nunca fue lanzado oficialmente.
  - Propuso cambios radicales, como un fuerte sistema de tipos, pero fue abandonado debido a diferencias entre Microsoft y otros actores clave.
  - Más información en ([ECMAScript 4: The missing version](https://evertpot.com/ecmascript-4-the-missing-version/))

**ECMAScript 5 (2009)**:
  - Soporte nativo de JSON (JSON.parse, JSON.stringify).
  - Modo estricto ("use strict";) para evitar errores comunes.
  - Nuevos métodos para arrays (forEach, map, filter, reduce).
  - Métodos para Object (Object.keys, Object.create).

**ECMAScript 6 (ES6) - 2015**:
  - Introducción de let y const.
  - Clases (class) y herencia (extends).
  - Funciones flecha (()=>{}).
  - Desestructuración (const {x, y} = objeto;).
  - Módulos (import/export).
  - Promesas (Promise) para manejar asincronía.
  - Template literals con backticks (`Hola ${nombre}`).
  - Parámetros por defecto y el operador rest (...args).

**ECMAScript 2016 (ES7)**:
  - Array.prototype.includes() para buscar elementos en arrays.
  - Operador de exponenciación (**), equivalente a Math.pow().

**ECMAScript 2017 (ES8)**:
  - async/await, facilitando el manejo de asincronía.
  - Object.entries() y Object.values() para trabajar con objetos.
  - String.prototype.padStart() y padEnd() para formateo de strings.

**ECMAScript 2018 (ES9)**:
  - Rest/Spread en objetos ({...obj}).
  - Promise.prototype.finally().
  - Mejoras en expresiones regulares (dotAll flag s).

**ECMAScript 2019 (ES10)**:
  - Array.prototype.flat() y flatMap() para manipulación de arrays anidados.
  - Object.fromEntries() (inverso de Object.entries()).
  - String.prototype.trimStart() y trimEnd().
  - Mejor manejo de catch (try { ... } catch {} sin parámetro de error).

**ECMAScript 2020 (ES11)**:
  - Encadenamiento opcional (?.) para acceder a propiedades sin errores (obj?.prop).
  - Operador de fusión nula (??) para valores nulos o undefined.
  - Promise.allSettled().
  - Imports dinámicos (import()) para carga de módulos bajo demanda.
  - BigInt (123n), permitiendo números mayores a Number.MAX_SAFE_INTEGER.

**ECMAScript 2021 (ES12)**:
  - String.prototype.replaceAll().
  - Métodos privados en clases (#propiedadPrivada).
  - Separadores numéricos (1_000_000 en vez de 1000000).
  - Promesas con any() (Promise.any()).

**ECMAScript 2022 (ES13)**:
  - Object.hasOwn(obj, prop), alternativa más segura a obj.hasOwnProperty(prop).
  - Top-level await, permitiendo await fuera de async function.
  - Mejoras en parámetros de catch.

**ECMAScript 2023 (ES14)**:
  - Métodos findLast() y findLastIndex() en arrays.
  - Array.prototype.toSorted(), toSpliced(), with(), introduciendo métodos inmutables.
  - Nuevas mejoras en RegExp y Set.

**ECMAScript 2024 (ES15)**:
  - Set Operations: Métodos como .union(), .intersection(), .difference() y .symmetricDifference() en Set.
  - Método Array.prototype.group() y groupToMap().
  - Nuevas mejoras en TypedArray.

**ECMAScript 2025 (ES16) (Estimado, basado en tendencias recientes)**:
  - Expresiones de coincidencia (match statement): Similar a switch, pero más flexible.
  - Optimización de iteradores en for-await-of.
  - Mejoras en performance y seguridad para WebAssembly y TC39 Proposals.

**Documentación Oficial**: [ECMAScript](https://tc39.es/ecma262/)

**Otra documentación consultada**: [La especificación ECMAScript](https://lenguajejs.com/javascript/introduccion/ecmascript/)

## 9. Características Destacables

- **Interpretado**: No necesita compilación previa, se ejecuta directamente en el navegador.

- **Multiplataforma**: Compatible con cualquier sistema operativo.

- **Asíncrono**: setTimeout, fetch, async/await permiten manejar eventos sin bloquear la ejecución.

- **Flexible**: Se usa tanto en frontend como en backend.

- **Comunidad Activa**: Uno de los lenguajes con mayor cantidad de repositorios en GitHub.

**Documentación Oficial**: [JavaScript en MDN]()

## 10. Enlaces Externos

- **Documentación Oficial**: [MDN JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)

- **Tutoriales Gratuitos**: [JavaScript.info](https://javascript.info/)

- **Comunidad**: [r/javascript en Reddit](https://www.reddit.com/r/javascript/)

- **Eventos**: [JSConf](https://jsconf.com/)