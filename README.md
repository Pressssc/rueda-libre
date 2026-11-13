Rueda Libre

Rueda Libre es un sitio web de alquiler de bicicletas y recorridos guiados en Medellín. Desde la página de inicio puedes explorar la flota y las promociones, comparar precios y rutas, y probar el formulario de reserva.

Ver el sitio en GitHub Pages
Páginas del sitio
Página	Qué puedes encontrar
[Inicio](index.html)	Carrusel de promociones, catálogo de siete tipos de bicicletas con precios por hora y pasos para alquilar.
[Tarifas y rutas](paginas/tarifas.html)	Tabla de precios para una hora, medio día o día completo. Incluye tres recorridos guiados con su dificultad, distancia, duración y precio por persona.
[Reservas](paginas/reservas.html)	Formulario con nombre, correo, tipo de servicio y fecha. Las políticas de alquiler se pueden consultar en una ventana emergente.


El formulario valida los campos en el navegador y sirve como demostración. Las reservas reales requerirían un servicio que reciba y guarde los datos. El correo, el enlace de WhatsApp y el enlace de ubicación son de ejemplo.
Tecnologías
- HTML5 para la estructura de las páginas y los campos del formulario.
- CSS para los colores, los botones y otros estilos propios del sitio.
- Bootstrap 5.3.3 para el diseño adaptable, las tarjetas, el carrusel y la ventana de políticas.
- Bootstrap Icons 1.11.3 para los íconos.
- JavaScript para aplicar la validación del formulario de reserva.

Estructura del proyecto

rueda-libre/

├── index.html

├── css/

│   └── estilos.css

├── img/

├── paginas/

│   ├── reservas.html

│   └── tarifas.html

└── pruebas/
    └── catalogo-booststrap.html
   
  css/estilos.css contiene los estilos compartidos por las páginas principales.
    img/ guarda las imágenes del sitio y pruebas/catalogo-booststrap.html reúne ejemplos de componentes
    de Bootstrap usados para practicar el diseño del catálogo.
