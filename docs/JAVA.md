# Java: Un Lenguaje Robusto y Multipropósito

## 1. Historia del Lenguaje
Java fue creado por **James Gosling** y su equipo en **Sun Microsystems** a principios de los años 90 como parte del proyecto **Green**, cuyo objetivo era desarrollar software para dispositivos electrónicos de consumo (como televisores interactivos). 

- **Nombre Original**: El lenguaje se llamaba **Oak** (en honor a un roble que Gosling veía desde su oficina), pero debido a conflictos legales, fue renombrado **Java** (inspirado en el café de la marca Java, popular entre el equipo, además esta variedad de café se consumía tanto, que en algunos lugares se utiliza el término JAVA para referirse al café de forma general.  Por todo ello, el logotipo de JAVA es una taza de café.).
- **Lanzamiento**: La primera versión pública, **Java 1.0**, se lanzó en 1996 bajo el eslogan **"Write Once, Run Anywhere" (WORA)**, gracias a la **Java Virtual Machine (JVM)**.
- **Hitos Importantes**:
  - **1999**: Lanzamiento de **Java 2 Platform (J2SE, J2EE, J2ME)**.
  - **2006**: Java se convierte en **código abierto** bajo la licencia GPL con el proyecto **OpenJDK**.
  - **2010**: Oracle adquiere Sun Microsystems y se convierte en el custodio principal de Java.
  - **2014**: **Java 8** introduce lambdas y streams, revolucionando el paradigma funcional.
  - **2021**: **Java 17** es una versión LTS (Long-Term Support) con mejoras en rendimiento y seguridad.

**Documentación Oficial**: [Historia de Java](https://www.oracle.com/es/java/)

---


## 2. Campo de Aplicación
Java es un pilar en la industria tecnológica, utilizado en:

- **Aplicaciones Empresariales**:
  - **Spring Framework**: Dominante en sistemas bancarios, ERP (SAP) y comercio electrónico.
  - Ejemplos: **Airbnb**, **Uber** (backend), **NASA World Wind** (visualización de datos geoespaciales).

- **Desarrollo Android**:
  - Aunque Kotlin es ahora el lenguaje preferido para Android, Java sigue siendo ampliamente usado.
  - Ejemplos: **Spotify**, **Twitter**, **Signal** (partes de su código base).

- **Big Data**:
  - **Apache Hadoop** y **Apache Spark** (procesamiento distribuido) están escritos en Java.
  - Ejemplos: **Netflix** (análisis de datos de usuarios), **LinkedIn** (recomendaciones).

- **Internet de las Cosas (IoT)**:
  - **Java ME Embedded** y **Eclipse IoT** se usan en dispositivos como sensores industriales y wearables.

- **Videojuegos**:
  - **Minecraft** (la versión original fue escrita en Java).
  - **LibGDX**: Framework para desarrollo de juegos multiplataforma.

**Documentación Oficial**: [Casos de Uso de Java](https://www.oracle.com/java/technologies/industries.html)

---

## 3. Tipado de Variables y Paradigmas
- **Tipado Estático y Fuerte**: Las variables deben declararse con su tipo (ej: `int numero = 5;`), y no se permiten operaciones entre tipos incompatibles.
- **Paradigmas**:
  - **Orientación a Objetos Pura**: Todo (excepto los tipos primitivos como `int` o `boolean`) es un objeto.
  - **Funcional** (desde Java 8): Lambdas (`(a, b) -> a + b`), streams y métodos de referencia.
  - **Concurrente**: Soporte nativo para hilos (`Thread` y `Runnable`).
- **Ejecución**:
  - **Compilado a Bytecode**: El código se compila en archivos `.class` que la JVM interpreta.
  - **JIT Compilation**: La JVM optimiza el código en tiempo de ejecución para mejorar el rendimiento.

**Documentación Oficial**: [Guía de Tipado en Java](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

---

## 4. Curiosidades
### a) **Java vs. JavaScript**
- A pesar del nombre, **no tienen relación directa**. JavaScript fue nombrado así por razones de marketing cuando Java estaba en auge.

### b) **El Misterio de Duke**
- **Duke**, el muñeco animado que es la mascota de Java, fue creado en 1992 por Joe Palrang (quien luego trabajó en películas como *Shrek*).

### c) **Java en el Espacio**
- El **Mars Rover Spirit** de la NASA utilizó Java para tareas de planificación y visualización de rutas.

### d) **El Gran Litigio Oracle vs. Google**
- Oracle demandó a Google en 2010 por usar APIs de Java en Android. Tras una década de disputas, en 2021 la Corte Suprema de EE.UU. falló a favor de Google, considerando el uso de APIs como "fair use".

### e) **Java en lo Inesperado**
- **Tarjetas SIM**: Java Card se usa en tarjetas inteligentes para almacenar datos de forma segura.
- **Cajeros Automáticos**: Muchos funcionan con aplicaciones Java.

### f) **Java y los Videojuegos**
- **Minecraft** (2009) fue creado por Markus Persson ("Notch") en Java. Aunque Microsoft reescribió partes en C++, la comunidad aún mantiene mods en Java.

**Documentación Oficial**: [Curiosidades de Java](https://dev.java/learn/)

---

## 5. IDEs y Herramientas
- **IntelliJ IDEA** ([Sitio Oficial](https://www.jetbrains.com/idea/)): El IDE más popular para Java, con soporte avanzado para Spring y Android.
- **Eclipse** ([Sitio Oficial](https://www.eclipse.org/)): Famoso por su flexibilidad y plugins como **Eclipse JDT**.
- **Visual Studio Code** ([Extensión Java](https://code.visualstudio.com/docs/languages/java)): Ligero pero potente con extensiones como **Language Support for Java™**.
- **Apache Maven** ([Sitio Oficial](https://maven.apache.org/)): Herramienta de gestión de dependencias y construcción de proyectos.

---

## 6. Frameworks y Bibliotecas
- **Spring Boot** ([Sitio Oficial](https://spring.io/projects/spring-boot)): Simplifica el desarrollo de aplicaciones empresariales con convención sobre configuración.
- **Hibernate** ([Sitio Oficial](https://hibernate.org/)): ORM (Mapeo Objeto-Relacional) para interactuar con bases de datos.
- **Micronaut** ([Sitio Oficial](https://micronaut.io/)): Diseñado para microservicios y aplicaciones nativas en la nube.
- **Vert.x** ([Sitio Oficial](https://vertx.io/)): Framework reactivo para aplicaciones de alto rendimiento.

---