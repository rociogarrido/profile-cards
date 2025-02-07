![](https://github.com/Adalab/project-promo-m-module-2-team-6/blob/main/src/images/vegan-deburguer-icon.jpg)

# Profile Cards

Vegan Debuggers es una aplicación desarrollada con la finalidad de crear tarjetas digitales personalizables y virtuales que podrán ser compartidas.

Es una aplicación amigable y fácil de usar, que además colabora con el medio ambiente, ya que el generar tarjetas virtuales tiene las siguientes ventajas:

- Menor consumo de papel. En unos momentos en los que todas estamos concienciadas con el medio ambiente, ahorrar en papel es algo que hay que tener en cuenta.
- Menor coste. Las tarjetas de visita tradicionales conllevan un coste de impresión, diseño..., etc. Con las tarjetas de visita online todo esto nos lo ahorramos.
- Actualización continúa. Son muy sencillas de actualizar. ¿Un producto nuevo? ¿Un trabajo acabado digno de enseñar? No te preocupes: todo el mundo que tenga tu tarjeta virtual online verá siempre los cambios que realices.
- Fácil de compartir. Nuestras tarjetas de visita online se pueden compartir por mail, GitHub, Facebook, Twitter, Linkedin... Un montón de posibilidades que te facilitan la vida.

## Descripción del proyecto

Esta aplicación está conformada por dos páginas:

1. Página de inicio o Landing page.
   En esta página invitamos a la usuaria a crear su tarjeta virtual.
2. Página de creación de tarjeta.
   En la que encontramos las siguientes secciones:
   - Diseña: para selección de la paleta de colores para nuestra tarjeta.
   - Rellena: contiene los campos a rellenar por la usuaria con sus datos personales (nombre completo, puesto, email, teléfono, LinkedIn, GitHub y una foto).
   - Comparte: sección en la que creamos la tarjeta y que nos indica el link que compartiremos en las redes sociales.

## Cómo funciona:

1. Inicio.

Al cargar la página la usuria verá la landing page en la que debe clickar el botón 'comenzar' para ser dirigido a la página donde creará su tarjeta.

2. Creación de Tarjeta.

   1. En la sección 'Diseña' debes seleccionar una paleta de colores para tu tarjeta y podrás visualizar tu selección en el lado derecho de la página.
   2. En la sección 'Rellena' debes cumplimentar todos los campos con tus datos personales (nombre completo, puesto, email, teléfono, LinkedIn, GitHub), así como la foto de perfil.
   3. En la sección 'Comparte' encontrarás un botón denominado 'Crear tarjeta': debes hacer click en él para que se genere tu tarjeta y al mismo tiempo se creará el enlace que podrás compartir en Twitter, haciendo nuevamente click sobre el botón 'compartir en Twitter'.

   Como puedes comprobar, es muy fácil y rápido crear tu tarjeta. No pierdas más tiempo: prueba la aplicación y contribuye con el medio ambiente.

## Esquema de funcionamiento

![Esquema](https://github.com/Adalab/project-promo-m-module-2-team-6/blob/main/src/images/Esquema.jpg)

## Herramientas empleadas

- Adalab web starter kit, que es una plantilla de proyecto con funcionalidades preinstaladas y preconfiguradas, que nos facilita la automatización de tareas, ya que incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local y muchas cosas más, que nos ayudan a trabajar más cómodamente, debido a la automatización de tareas.

- Editor de código Visual Studio Code

- Node JS

- Git

**NOTA:** Estas herramientas son las requeridas para poder utilizar o colaborar en el proyecto.

## Estrucutra de las carpetas

```
src
├─ api // los ficheros de esta carpeta se copian en public/api/
|  └─ data.json
├─ js // los ficheros de esta carpeta se concatenan en el fichero main.js y este se guarda en public/main.js
|  ├─ main.js
|  └─ events.js
├─ scss
|  ├─ core
|  |  ├─ reset
|  |  └─ variables
|  └─ layout
|     ├─ design
|     ├─ fill
|     ├─ footer
|     ├─ header
|     ├─ landing-page
|     ├─ main-card
|     ├─ page
|     ├─ palette
|     ├─ photo
|     └─ share
└─ html
|  └─ partials
|     ├─ design
|     ├─ fill
|     ├─ footer
|     ├─ header
|     ├─ main-cards
|     ├─ main
|     ├─ photo
|     └─ share
└─ js
   └─ partials
      ├─ 00_collapsible
      ├─ 01_form
      ├─ 02_palette
      ├─ 03_photo
      ├─ 04_reset
      ├─ 05_localStorage
      └─ 06_fetch
```
