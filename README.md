<!-- TÍTULO Y DESCRIPCIÓN -->
  <a name="ir-arriba"></a>
  # 💻 Encuesta de satisfacción de Indira Hotel Boutique

  Proyecto N°1 para la certificación de Diseño Web Adaptativo correspondiente a **freeCodeCamp**
  <div align="center">
    <table>
      <tr>
        <td>
          <p>Consigna: Construye un formulario en HTML y CSS</p>
          <p>Objetivo: Crea una aplicación que sea funcionalmente similar a https://survey-form.freecodecamp.rocks</p>
        </td>
        <td>
          <img src="https://github.com/jc-projects/freeCodeCamp_Encuesta/blob/main/img/imgREADME.gif" width="400px">
        </td>
      </tr>
    </table>
  </div>

<!-- ÍNDICE -->
  <a name="indice"></a>
  ## 📌 Índice
  <ol>
    <li><a href="#ir-arriba">Título y descripción del proyecto</a></li>
    <li><a href="#indice">Índice</a></li>
    <li><a href="#tecnologias">Tecnologías utilizadas</a></li>
    <li><a href="#historias-de-usuario">Historias de usuario</a></li>
    <li><a href="#pruebas">Pruebas</a></li>
    <li><a href="#desarrollado">Desarrollado por...</a>
    <li><a href="#contacto">Contacto</a>
    <li><a href="#agradecimiento">Agradecimiento</a>
  </ol>

<!-- TECNOLOGÍAS UTILIZADAS -->
  <a name="tecnologias"></a>
  ## ✅ Tecnologías utilizadas
  <p align="center">
    <a href="https://en.wikipedia.org/wiki/HTML5" target="_blank">
      <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white">
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank">
      <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white">
    </a>
    <a href="www.netlify.com" target="_blank">
      <img src="https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7">
    </a>
   </p>
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- HISTORIAS DE USUARIO -->
  <a name="historias-de-usuario"></a>
  ## 🔧 Historias de usuario
  1. Debes tener un título de página en un elemento `h1` con un `id` de `title`
  2. Debes tener una corta explicación en el elemento `p` con un `id` de `description`
  3. Debes tener un elemento `form` con un `id` de `survey-form`
  4. Dentro del elemento form, debe ser <b>required</b> (requerido) ingresar tu nombre en un campo de `input` que tenga un `id` de `name` y un `type` de `text`
  5. Dentro del elemento form <b>required</b> (requerido) ingresar tu nombre en un campo de `input` que tenga un `id` de `email`
  6. Si ingresas un email que no tenga el formato correcto, verás un error de validación HTML5
  7. Dentro del formulario, puedes ingresar un número en un campo de `input` que tenga un `id` de `number`
  8. La entrada de números no debe aceptar caracteres no numéricos, ya sea impidiendo que los escribas o mostrando un error de validación HTML5 (dependiendo del navegador)
  9. Si ingrisas un número que esté fuera del rango de números permitido, que es definido por los atributos `min` y `max`, verás un error de validación de HTML5
  10. Para los campos de entrada de nombre, email y número, puedes ver los correspondientes elementos `label` en el formulario, que describen el propósito de cada campo con los siguientes id: `id="name-label"`, `id="email-label"` y `id="number-label"`
  11. Para los campos de entrada de nombre, email y número, podrás ver un texto provisional que da una descripción o instrucciones para cada campo
  12. Dentro del elemento form, debes tener un elemento desplegable `select` con un `id` de `dropdown` con al menos dos opciones para elegir
  13. Dentro del elemento form, puedes seleccionar una opción de un grupo de al menos dos botones de radio que son agrupado utilizando el atributo `name`
  14. Dentro del elemento form, puedes seleccionar varios campos en una serie de casillas de verificación, cada una debe tener un atributo `value`
  15. Dentro del elemento form, se te presenta un `textarea` para comentarios adicionales
  16. Dentro del elemento form, se te presenta un botón con un `id` de `submit` para enviar todas las entradas
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- PRUEBAS -->
  <a name="pruebas"></a>
  ## ⚙️ Pruebas
  <ul>
    <li>Debes tener un elemento <b>h1</b> con un <b>id</b> de <b>title</b></li>
    <li>Tu <b>#title</b> no debe estar vacío.</li>
    <li>Debes tener un elemento <b>p</b> con un <b>id</b> de <b>description</b></li>
    <li>Tu <b>#description</b> no debe estar vacío</li>
    <li>Debes tener un elemento <b>form</b> con un <b>id</b> de <b>survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> con un <b>id</b> de <b>name</b></li>
    <li>Tu <b>#name</b> debe tener un <b>type</b> de <b>text</b></li>
    <li>Tu <b>#name</b> debe requerir una entrada</li>
    <li>Tu <b>#name</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> con un <b>id</b> de <b>email</b></li>
    <li>Tu <b>#email</b> debe tener un <b>type</b> de <b>email</b></li>
    <li>Tu <b>#email</b> debe requerir una entrada</li>
    <li>Tú <b>#email</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> con un <b>id</b> de <b>number</b></li>
    <li>Tu <b>#number</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#number</b> debe tener un <b>type</b> de <b>number</b></li>
    <li>Tu <b>#number</b> debe tener un atributo <b>min</b> con un valor numérico</li>
    <li>Tu <b>#number</b> debe tener un atributo <b>max</b> con un valor numérico</li>
    <li>Debes tener un elemento <b>label</b> con un <b>id</b> de <b>name-label</b></li>
    <li>Debes tener un elemento <b>label</b> con un <b>id</b> de <b>email-label</b></li>
    <li>Debes tener un elemento <b>label</b> con un <b>id</b> de <b>number-label</b></li>
    <li>Tu <b>#name-label</b> debe contener un texto que describa la entrada</li>
    <li>Tu <b>#email-label</b> debe contener un texto que describa la entrada</li>
    <li>Tu <b>#number-label</b> debe contener un texto que describa la entrada</li>
    <li>Tu <b>#name-label</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#email-label</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#number-label</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#name</b> debe tener el atributo <b>placeholder</b> y un valor</li>
    <li>Tu <b>#email</b> debe tener un atributo <b>placeholder</b> y un valor</li>
    <li>Tu <b>#number</b> debe tener un atributo <b>placeholder</b> y un valor</li>
    <li>Debes tener un campo <b>select</b> con un <b>id</b> de <b>dropdown</b></li>
    <li>Tu <b>#dropdown</b> debe tener al menos dos elementos <b>option</b> seleccionables (no deshabilitados)</li>
    <li>Tu <b>#dropdown</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Debes tener al menos dos elementos <b>input</b> con un <b>type</b> de <b>radio</b> (botones de radio)</li>
    <li>Debes tener al menos dos botones de radio que sean descendientes de <b>#survey-form</b></li>
    <li>Todos tus botones de radio deben tener un atributo <b>value</b> y un valor</li>
    <li>Todos tus botones de radio deben tener un atributo <b>name</b> y un valor</li>
    <li>Cada grupo de botón de radio debe tener al menos 2 botones de radio</li>
    <li>Debes tener al menos dos elementos <b>input</b> con un <b>type</b> de <b>checkbox</b> (casillas de verificación) que sean descendientes de <b>#survey-form</b></li>
    <li>Todos tus casillas de verificación dentro de <b>#survey-form</b> deben tener un atributo <b>value</b> y un valor</li>
    <li>Debes tener al menos un elemento de <b>textarea</b> que sea descendiente de <b>#survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> o <b>button</b> con un <b>id</b> de <b>submit</b></li>
    <li>Tu <b>#submit</b> debe tener un <b>type</b> de <b>submit</b></li>
    <li>Tu <b>#submit</b> debe ser descendiente de <b>#survey-form</b></li>   
  </ul>
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- DESARROLLADO POR -->
  <a name="desarrollado"></a>
  ## 💁 Desarrollado por...
  * **Joana Coll** - [jc-projects](https://github.com/jc-projects)
  
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- CONTACTO -->
  <a name="contacto"></a>
  ## 📩 Contacto
  Si deseas contactarte conmigo podes hacerlo mediante mensaje privado a: 
  **[Instagram ](https://instagram.com/einenko) - [Github ](https://github.com/jc-projects)** 
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>

<!-- AGRADECIMIENTO -->
  <a name="agradecimiento"></a>
  ## ❤️ Agradecimiento
  Gracias por leer hasta aquí, espero que el proyecto te sea útil. No tiene Licencia pero podes usarlo como gustes mientras sigas fomentando el código libre y ayudando a otros pares. 
  
  ¡Que tengas un lindo día!
  
  Nana ✨
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
