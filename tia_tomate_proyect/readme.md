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

### Sketch Desktop Version:
![Sketch Desktop Version](assets/img/sketch_d.jpg =500x)
### Sketch Mobile Version:
![Sketch Desktop Version](assets/img/sketch_m.jpg =250x)

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
