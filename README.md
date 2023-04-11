# Levantamiento y comprension de la APP

## Presentación
* Asignatura: Analisis de sistemas
* Profesor: Lizandro Ramírez
* Estudiantes: Ismanol Ramírez 2020-0098, Miguel Concepción 2021-1375, Juan Manuel Flores 2020-0966

---

## Introducción

Este archivo readme.md presenta la documentación de una app web diseñada para almacenar información de usuarios en una base de datos Postgres y Redis, realizar cálculos complejos en un worker y presentar los resultados en una página web a través de un cliente React. La app se ha encapsulado en Docker con seis servicios que incluyen nginx, postgres, api, redis, cliente-react y worker.

Se explicará el marco teórico de los componentes y tecnologías utilizadas, se presentará una prueba de funcionamiento minuciosa y se destacarán los resultados y las posibles mejoras para el futuro.

---

## Marco teorico

El Marco Teórico es una revisión sistemática y crítica de la literatura y teorías existentes relacionadas con el tema en cuestión. En este apartado de la documentación estarán las diferentes definiciones de las herramientas o servicios utilizados para que este programa pueda funcionar. Con este marco teórico se tiene como objetivo dejar de forma más precisa los términos usados en este proyecto para el análisis de la app.

---

## React

React utiliza una sintaxis de lenguaje llamada JSX, que combina HTML y JavaScript para crear componentes reutilizables que se pueden utilizar para construir interfaces de usuario complejas. Los componentes en React se dividen en pequeñas partes, lo que hace que el código sea más fácil de mantener y actualizar.

Para comprender cómo funciona React es clave que nos situemos en un contexto, pues cuando se aprende desarrollo web se obtiene conocimiento de tres conceptos básicos:

* HTML: la semántica, estructura e información de la página web; es decir, su esqueleto.
* CSS: la apariencia de nuestra página web.
* JavaScript: básicamente es el cerebro de nuestra página. Determina qué hacer en función de lo que sucede en ella.

---

## Node.js

Node.js utiliza el motor de JavaScript V8 de Google para interpretar el código y proporciona una serie de módulos y herramientas que permiten a los desarrolladores crear aplicaciones web escalables y de alto rendimiento. Algunas de las características más destacadas de Node.js incluyen:

* Un modelo de E/S sin bloqueo y orientado a eventos que permite a Node.js manejar múltiples solicitudes simultáneamente sin bloquear el subproceso principal de la aplicación.
* Un sistema de módulos de código abierto que permite a los desarrolladores reutilizar el código y compartirlo con la comunidad de Node.js.
* Una amplia gama de herramientas y bibliotecas de terceros disponibles a través de NPM (Node Package Manager), que facilitan la construcción de aplicaciones web complejas y de alta calidad.

---

## API REST

Una API REST es una interfaz de comunicación entre sistemas de información que usa el protocolo de transferencia de hipertexto (HTTP) para obtener datos o ejecutar operaciones sobre dichos datos en diversos formatos, como pueden ser XML o JSON.

En la actualidad no existe proyecto o aplicación que no disponga de una API REST para la creación de servicios profesionales a partir de ese software. Twitter, YouTube, los sistemas de identificación con Facebook, hay cientos de empresas que generan negocio gracias a REST y las APIs REST.

---

## Docker

Docker es una tecnología que está en el mercado desde 2013. Se trata de un proyecto open source, uno de los más populares de Github. Con Docker, nos referimos al software que se dedica a la virtualización de aplicaciones o de espacios virtualizados.
Brinda una capa adicional de abstracción y automatización de virtualización de aplicaciones en múltiples sistemas operativos. Internamente, utiliza la tecnología de contenedores de Linux. Si bien los contenedores te permiten virtualizar, el sistema operativo sigue siendo el propio. 

---

## Nginx

Nginx (engine-x) es un servidor web y un servidor proxy inverso de código abierto y alto rendimiento. Fue creado por Igor Sysoev en 2002 y es utilizado por muchas empresas y sitios web populares debido a su capacidad para manejar grandes cargas de tráfico web con eficacia. Una de las principales características de Nginx es su capacidad para manejar múltiples conexiones de forma simultánea y eficiente, lo que lo hace adecuado para sitios web de alto tráfico.

---

## Worker

Un Service Worker es un trabajador (worker) en segundo plano que se ejecuta en el navegador web de un usuario y que proporciona funcionalidad de red a una aplicación web. Los Service Workers son una tecnología de JavaScript que se utiliza para mejorar el rendimiento y la capacidad de respuesta de las aplicaciones web, especialmente en dispositivos móviles. Algunas de las características y funciones que se pueden realizar con Service Workers incluyen:

* Cacheo de recursos para su uso sin conexión.
* Gestión de actualizaciones de la aplicación web en segundo plano.
* Redirección de solicitudes de red a servidores de respaldo o espejo en caso de interrupciones o problemas de conectividad.
* Gestión de notificaciones push en dispositivos móviles.

---

## PostgresSQL

PostgreSQL es un sistema de gestión de bases de datos relacionales de código abierto, también conocido como Postgres. Fue creado en 1986 en la Universidad de California en Berkeley, y desde entonces se ha convertido en uno de los sistemas de gestión de bases de datos más populares del mundo.
PostgreSQL es un sistema de base de datos avanzado y poderoso que soporta una amplia gama de características, incluyendo:

* SQL completo y compatible con los estándares ANSI SQL y SQL99.
* Soporte para funciones y procedimientos almacenados.
* Replicación y alta disponibilidad para aplicaciones críticas.
* Índices avanzados, incluyendo B-trees, GIN, GiST y SP-GiST.
* Soporte para JSON y otros formatos de datos semi-estructurados.

---

## Redis

Redis es una base de datos en memoria de código abierto que se utiliza para almacenar datos en caché y como almacenamiento de bases de datos en tiempo real. Fue creado por Salvatore Sanfilippo en 2009 y desde entonces se ha convertido en uno de los sistemas de bases de datos en memoria más populares del mundo.

---

## Conclusión

En conclusión, tras realizar un análisis exhaustivo de esta app, podemos apreciar la importancia y la complejidad de su estructura, así como la interconexión de sus herramientas y servicios. Es crucial destacar la relevancia de los componentes principales de la estructura, como el server, nginx y worker, que proporcionan los controles necesarios para el correcto funcionamiento de la aplicación. Además, aunque el diseño puede parecer superficial, es importante mencionar que el código JS es fundamental para realizar los cálculos complejos de Fibonacci, lo que lo convierte en una parte fundamental del programa. Teniendo en cuenta estos aspectos, podemos concluir que este programa es un excelente ejemplo de cómo la tecnología puede ser utilizada para crear soluciones innovadoras y eficientes.

---




