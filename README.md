# Web personal (maqueta de portfolio)

Práctica del bootcamp de Full Stack de The Bridge.

## Qué es

El portfolio de Sarah Chen, una estudiante de diseño inventada. El bootcamp nos dio el diseño ya hecho y el trabajo era maquetarlo con HTML y CSS lo más parecido posible. Los textos, los proyectos y las imágenes vienen del diseño.

Después usé esta misma web en la [práctica de Docker](https://github.com/jbalaguersalas/-Pr-ctica-Docker-Web-Minimalista), donde la sirvo con nginx.

## Qué hice

- **`index.html`**: cabecera con avatar, nombre y menú; una frase de presentación; cinco tarjetas de proyecto (Yoga studio rebrand, Abstract paintings, Magazine study, Echoes of Italy y Castro Capital branding); y un pie con enlaces.
- **`about.html`**: la página "About" con título, texto e imagen.
- **`project.html`**: el detalle de un proyecto, con etiqueta, título, descripción e imagen.
- **`styles.css`**: un solo archivo para las tres páginas.

Algunas cosas concretas del CSS:

- Uso nombres de clase BEM: `project-card`, `project-card__info`, `project-card__button`, `nav__link--active`.
- Empecé por el móvil. Luego añadí media queries a 600px, 800px y 1280px. A partir de 600px cada tarjeta pone el texto a la izquierda y la imagen a la derecha, y a partir de 800px crecen los tamaños de letra.
- Dos tipografías: Newsreader (de Google Fonts) para los textos grandes y Arial para el menú, las etiquetas y los botones.

## Cómo verlo

Descarga el repositorio y abre `index.html` en el navegador. No hay que instalar nada.
