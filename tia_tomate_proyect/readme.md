# Ejercicio 09 - Maquetación

## Pre-maquetado de página Tía Tomate

### Requerimientos generales:

- Landing Web page Responsive (Acerca de)
    - Historia
    - Origen de Productos
    - Equipo
    - Énfasis en la compra (Call to Action)
- Navbar de 4 elementos
    - Acerca de
    - Productos
    - Blog
    - Contacto
- 4 Secciones:
    - Header
    - Origen
    - About us
    - Call to action
- Footer:
    - Rrss
    - 4 links de navbar

### Requerimientos específicos:

- Icons:
    - Background: white
    - Rounded
    - Font Awesome
- Textos
    - Falta título de segunda secciónav
    - Los parrafos son simulados (será tarea de content manager)
- Grid system:
    - Bootstrap
        - Navbar: 6 col - 6 col
        - Header: 12 col
        - Origen: 7 col - 5 col
        - About us title: 12 col
        - About us: 6 col - 6 col
        - Call to action: 12 col
        - Footer: 3 col - 3 col - 3 col

### Requerimientos visuales:

- Layout:
    - Bootstrap
- Tipografía:
    - Titles h1: Raleway bold, extra-light
    - h2: Raleway extra-bold
    - p: Open Sans Regular
- Colores:
    - Navbar, background icons, h1 & p: #ffffff
    - Background header: #e56353
    - Background section: #707070 | #fafafa
    - Footer & p: #686963
- Imágenes:
    - Están todas
- Icons:
    - Font-Awesome

### Sketch Desktop Version: (img/sketch_d.jpg)

### Sketch Mobile Version: (img/sketch_m.jpg)

### Estructura:

    - navbar
    - main
        - header
        - origen
        - about
        - cta
    - footer

### Clases:

    - navbar
        - navbar__brand
        - navbar__navigation
    - header
    - Origen
        - origen__inner
            - origen__inner--background-left
            - origen__inner--background-right
    - about
        - about__inner
            - about__inner--img
    - cta
        - cta__button
    - footer
        - footer__brand
        - footer__rrss
        - footer__navigation

Aplicando todo los conceptos y herramientas aprendidas en la experiencia online de maquetación, planifica la construcción de la página web de "Tía Tomate".

Revisa el mockup [aquí](img/tiatomate-desktop.png).

![Mockup blog barbería](img/tiatomate-desktop.png)

La empresa productora de tomates orgánicos llamada **Tía Tomate** pide crear una maqueta de la página "acerca de".

En ella desean mostrar a sus clientes una pequeña reseña sobre su historia, la procedencia de sus productos y mostrar a las personas que trabajan cosechando estas verduras.

Según sus requerimientos la página debe:

- Ser responsiva
- Mostrar la pasión que sienten por sus tomates
- Dar enfásis a la compra de sus productos
- Mostrar el logo de la empresa

El diseñador del mockup envío una [guía de estilos](img/tiatomate-guia-de-estilos.png) con las imágenes, colores y fuentes que usó para crear esta representación visual (puedes encontrar los assets en el siguiente [link](../assets)).

Además, ellos comentan que crearán el contenido de su página web con la persona encargada de mantener sus redes sociales.

### Requsitos generales:

Teniendo todo esto en cuenta deberás:

- Entender todos los requerimientos visuales y técnicos de la página web.
- Crear un listado resumiendo todos los requerimientos recopilados a través del desafío.
- Construir un sketch el cuál muestre las secciones de la página, junto con la estructura HTML y CSS (clases) que decidiste hacer para esta.
- Crear otro sketch que muestre la página web pero esta vez para dispositivos móviles.
-	Crear la estructura de directorios de la página web.
-	Agregar todas las dependencias necesarias para la web.

**Si aún te queda tiempo comienza a construir la página web.**

Luego de terminar, documenta todo el proceso que hiciste dentro de un **README.md**, agregando:

- Un listado con los requerimientos visuales y técnicos de la web.
- Una foto con los sketch de la versión escritorio y móvil.
- Una descripción de las secciones, layout, estructura HTML y clases CSS que decidiste usar.

Además debes agregar la estructura de directorio que hiciste, junto con las dependencias y otros archivos necesarios usados en el proyecto.

### Criterios de evaluación:

- Organización de los requerimientos
- Utilización de BEM para la creación de clases CSS
- Descripción de los layout y secciones
- Creación de sketch para formato móvil y de escritorio
- Creación de los directorios
- Integración de dependencias y otros archivos necesarios en los directorios
- Creación de README.md con todo el proceso documentado
- Uso de GIT para versionar el desafío
- Creación de repositorio con el desafío
- Entrega del desafío a través de la plataforma desafío

Luego de terminar debes enviar los cambios (vía push) y subir el link del repositorio a la sección correspondiente en la plataforma [empieza](https://empieza.desafiolatam.com "Desafío Latam").

Mucha suerte!
