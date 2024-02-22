# Tittle_Ring_light_effect
# Descripción del Efecto Interactivo en el Título
Este proyecto incorpora un efecto visual interactivo utilizando HTML, CSS y JavaScript, donde un aro circular animado se crea alrededor del cursor cuando este pasa sobre el título de la página. Este efecto se logra mediante una combinación de animaciones CSS y manipulación del DOM con JavaScript.

# Estructura HTML
La página está estructurada con un elemento <div> principal que actúa como contenedor, dentro del cual se encuentra el <h1> que sirve de título.
Un segundo <div> actúa como pie de página.
# Estilos CSS
Los estilos CSS aplican un tema oscuro general a la página, centran el contenido y definen animaciones específicas para el título y el aro circular.
Se utiliza una animación de "palpitación" para el título y una animación de "onda de luz" para el aro circular, que se activa al interactuar con el título.
El aro circular se estiliza para ser transparente, con un borde azul sólido y una opacidad reducida.
# Funcionalidad JavaScript
El script JavaScript define una función createCircle, que se invoca cuando el mouse pasa sobre el título.
Esta función crea dinámicamente un nuevo elemento <div> con una clase .circle, posicionándolo en el lugar del cursor en el momento de la interacción.
El aro se anima para expandirse y desvanecerse, simulando una onda que se aleja del punto de contacto.
Una vez completada la animación, el aro se elimina del DOM para mantener limpia la estructura de la página.
