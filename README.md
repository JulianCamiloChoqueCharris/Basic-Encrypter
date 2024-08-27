🍪 Encriptador de Texto - Challenge Alura + Oracle

📄 Descripción

Este proyecto es parte del challenge de Alura en colaboración con Oracle y tiene como objetivo desarrollar un encriptador y desencriptador de texto utilizando una técnica sencilla. El encriptador convierte letras en secuencias de texto predeterminadas y puede revertir este proceso para obtener el texto original.

El proyecto está desarrollado en HTML, CSS y JavaScript, y está diseñado para mejorar las habilidades de programación en el frontend.

🚀 Tecnologías Utilizadas

HTML5
CSS3
JavaScript

✅ Requisitos
Solo se permiten letras minúsculas.
No deben utilizarse acentos ni caracteres especiales.
El usuario puede:
Encriptar una palabra.
Desencriptar una palabra encriptada y devolverla a su versión original.

🔩 Funcionamiento

🔒 Encriptación

El proceso de encriptación se basa en la sustitución de vocales por secuencias de caracteres específicos. La tabla a continuación muestra las reglas de conversión:
Entrada Salida

e enter
i imes
a ai
o ober
u ufat

Ejemplo:

"gato" => "gaitober"

🔓 Desencriptación

El proceso de desencriptación revierte las secuencias de caracteres en las vocales originales, utilizando las siguientes reglas:
Entrada Salida

enter e
imes i
ai a
ober o
ufat u

Ejemplo:

"gaitober" => "gato"

📂 Estructura del Proyecto

/
├── index.html
├── src/
│ ├── css/
│ │ ├── normalize.css
│ │ └── styles.css
│ ├── img/
│ ├── js/
│ │ ├── app.js
│ │ ├── variables.js
│ │ └── functions/
│ │ ├── decrypt.js
│ │ ├── encrypt.js
│ │ └── utils.js
