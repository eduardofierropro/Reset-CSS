![Imagen del proyecto](https://github.com/eduardofierropro/Reset-CSS/blob/main/assets/home1.jpg)

# Reset CSS PRO

Reset CSS Pro un reset personalizable que combina las líneas de los reset más usados y añade algunos extras para que maquetar en tu proyecto sea sencillo. Es el que uso a nivel personal y solventa problemas como:

* Unificar el uso de Custom Properties
* Problemas de box-model más generales
* Problemas con imagenes, vídeos e iconos svg
* Problemas con tipografías y etiquetas input en formularios
* Unificar la tipografía de todas las etiquetas de una web
* Añade la nu

[![Configurador en resetcss.pro](https://img.shields.io/static/v1?label=&message=Ir%20en%20resetcss.pro&color=000000&style=for-the-badge)](https://resetcss.pro/)
[![Youtube](https://img.shields.io/static/v1?label=&message=aprender%20teoria&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/bXqPNoYFK8w)
[![Youtube](https://img.shields.io/static/v1?label=&message=explicación%20del%20código&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/Foieq2jTajE)

## Instalación en NPM

Primero debes de instalarlo en tu proyecto con:

```bash
npm i reset-css-pro 
```

Después dentro del proyecto puedes importarlo desde Javascript o desde CSS, por ejemplo si estás usando Vite en el archivo `App.jsx` puedes añadir:

```js
import 'reset-css-pro'
```

Y otra opción desde el archivo `index.css` puedes añadir:
```css
@import 'reset-css-pro';
```

## Instalación en proyecto sencillo de HTML y CSS
Puedes ir a la web [resetcss.pro](https://resetcss.pro) y copiarlo directamente desde el configurador para probarlo.

[![Configurador en resetcss.pro](https://img.shields.io/static/v1?label=&message=Ir%20en%20resetcss.pro&color=ffffff&style=for-the-badge)](https://resetcss.pro/)

## Configuración del reset para NPM
La idea de un reset es que se adapte a tu forma de maquetar, y puedes configurarlo para sólo usar ciertas partes del reset que mejor se adapten a tí.


### Tanto en CSS...
```css
@import 'reset-css-pro';           /* Incluye todo el reset                 */
@import 'reset-css-pro/anchor';    /* Incluye sólo para los enlaces         */
@import 'reset-css-pro/body';      /* Incluye sólo el body                  */
@import 'reset-css-pro/box-model'; /* Incluye sólo el clásico *{margin:0}   */
@import 'reset-css-pro/forms';     /* Incluye sólo reset de formularios     */
@import 'reset-css-pro/list';      /* Incluye sólo los puntos de la lista   */
@import 'reset-css-pro/media';     /* Incluye sólo imágenes, video e iframes*/
@import 'reset-css-pro/motion';    /* Incluye sólo eliminar animaciones en reduced-motion */
@import 'reset-css-pro/smooth-anchor';    /* Incluye  sólo anclas suaves    */
@import 'reset-css-pro/svg';       /* Incluye sólo etiquetas svg            */
@import 'reset-css-pro/table';     /* Incluye sólo reset para tablas        */
@import 'reset-css-pro/typography';/* Incluye sólo el reset de tipografías  */
```

### ... como en Javascript
```js
import 'reset-css-pro';                 // Incluye todo el reset                 
import 'reset-css-pro/anchor';          // Incluye sólo para los enlaces         
import 'reset-css-pro/body';            // Incluye sólo el body                  
import 'reset-css-pro/box-model';       // Incluye sólo el clásico *{margin:0}   
import 'reset-css-pro/forms';           // Incluye sólo reset de formularios     
import 'reset-css-pro/list';            // Incluye sólo los puntos de la lista   
import 'reset-css-pro/media';           // Incluye sólo imágenes, video e iframes
import 'reset-css-pro/motion';          // Incluye sólo eliminar animaciones en reduced-motion 
import 'reset-css-pro/smooth-anchor';   // Incluye  sólo anclas suaves    
import 'reset-css-pro/svg';             // Incluye sólo etiquetas svg            
import 'reset-css-pro/table';           // Incluye sólo reset para tablas        
import 'reset-css-pro/typography';      // Incluye sólo el reset de tipografías  
```

## ¿Qué problemas resuelve?

* Definición básica de Custom properties con tipografías y colores
  * *Opcional* Custom Properties en modo oscuro
  * *Opcional* Configuramos si un usuario ha activado el modo alto contraste *(WD)*
* Reset de margin, paddings y border de todas las etiquetas 
* Evitamos problemas con las imagenes con recomendaciones de Microsoft
  * *Opcional*  object-fit: cover;        
  * *Opcional*  object-position: center center;
* Reset para las anclas que funcionen como cajas excepto los que se encuentran en párrafos 
  * *Opcional* Configuramos anclas suaves 
* Quitamos los puntos de los `<li>` 
* Desactivamos estilos por defecto de las principales etiquetas de texto 
* Evitamos problemas con los pseudoelementos de *quotes* 
* Configuramos el selection de una web en base al color principal
* Reset de los problemas tipográficos y la colocación de elementos de formularios 
  * *Opcional*  appearance: none;
* Reseteamos las tablas 
* Evitamos problemas con los SVG 
* Configuramos la tipografía para toda la web
    * *Opcional* Configuración de interlineado
    * *Opcional* Problemas con palabras largas gracias a hyphens
    * *Opcional* Tipografía más suave en macOS gracias a font-smooth


## 📥 Descarga el PDF con todos los módulos
Aquí te dejo [un enlace de descarga hacia un PDF](https://eduardofierro.pro/descargas/modulos-de-una-web.pdf?utm_source=modulos-web&utm_medium=github&utm_campaign=descarga-pdf) con el resto de módulos, resumen y teoría.


## 🔴 Vídeos relacionados con el reset

| Nombre | Youtube |
|--|--|
|Reset CSS: Teoría|[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20video&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/bXqPNoYFK8w)|
|Reset PRO: Código|[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20video&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/Foieq2jTajE)|
|Nomenclaturas CSS|[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20video&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/lhEJkeCJ3As)|
|Metodologías CSS|[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20video&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/f0LpZoyY1gE)|
|Arquitecturas CSS|[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20video&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/tUldrlfIGb4)|


## 💻 Repositorios y vídeos relacionados

En estos repositorios tendrás acceso a todas las versiones de cada módulo creadas con diferentes tecnologías como HTML, SCSS, TS, Angular, ReactJS...
Para que puedas practicar con un código básico.

| Nombre | Playlist | Repositorio | 
|--|--|--|
|Menú Responsive |[![Youtube](https://img.shields.io/static/v1?label=&message=ver%2020en%20playlist&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://www.youtube.com/playlist?list=PLJpymL0goBgFA5iTweWRejUhBP9TSSNnw)|[![github](https://img.shields.io/static/v1?label=&message=ver%20repo&color=171515&logo=github&logoColor=white&style=for-the-badge)](https://github.com/eduardofierropro/eduardofierropro-Como-crear-un-menu-hamburguesa-horizontal)|
<!-- |Slider con HTML, CSS y JS |[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20en%20playlist&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](XXXX)|[![github](https://img.shields.io/static/v1?label=&message=ver%20repo&color=171515&logo=github&logoColor=white&style=for-the-badge)](XXXX)|
|Carrousel con HTML, CSS y JS |[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20en%20playlist&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](XXXX)|[![github](https://img.shields.io/static/v1?label=&message=ver%20repo&color=171515&logo=github&logoColor=white&style=for-the-badge)](XXXX)|
|Lightbox con HTML, CSS y JS |[![Youtube](https://img.shields.io/static/v1?label=&message=ver%20en%20playlist&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](XXXX)|[![github](https://img.shields.io/static/v1?label=&message=ver%20repo&color=171515&logo=github&logoColor=white&style=for-the-badge)](XXXX)| -->

## 👨🏻‍🏫 Eduardo Fierro Pro
 
¡Qué pasa cruck! Soy profesor de programación tanto en escuelas como en Bootcamps y en mis tiempos libres programo por Twitch y en Youtube.

[![Youtube](https://img.shields.io/static/v1?label=&message=youtube&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://youtube.com/EduardoFierroPro?sub_confirmation=1)
[![twitch](https://img.shields.io/static/v1?label=&message=twitch&color=6441a5&logo=twitch&logoColor=white&style=for-the-badge)](https://twitch.tv/eduardofierropro)
[![tiktok](https://img.shields.io/static/v1?label=&message=tiktok&color=ff0050&logo=tiktok&logoColor=white&style=for-the-badge)](https://www.tiktok.com/@eduardofierro.pro?)
[![instagram](https://img.shields.io/static/v1?label=&message=instagram&color=5B51D8&logo=instagram&logoColor=white&style=for-the-badge)](https://instagram.com/eduardofierro.pro)
[![linkedin](https://img.shields.io/static/v1?label=&message=linkedin&color=0e76a8&logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/eduardofierropro)
[![discord](https://img.shields.io/static/v1?label=&message=discord&color=7289da&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/t4Txush)
[![twitter](https://img.shields.io/static/v1?label=&message=twitter&color=1DA1F2&logo=twitter&logoColor=white&style=for-the-badge)](https://twitter.com/edfierropro)
[![github](https://img.shields.io/static/v1?label=&message=github&color=171515&logo=github&logoColor=white&style=for-the-badge)](https://github.com/eduardofierropro)
[![colaboración](https://img.shields.io/static/v1?label=&message=MIS%20CURSOS&color=blue&logo=teach&logoColor=white&style=for-the-badge)](http://colaboracion.eduardofierro.pro)


## 📄 Licencia 

MIT Public License v3.0
No puede usarse comercialmente
