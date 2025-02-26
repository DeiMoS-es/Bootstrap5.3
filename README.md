# Bootstrap 5.3

## Historia de Bootstrap

Bootstrap es un framework de código abierto para el desarrollo de interfaces de usuario y sitios web responsivos. Fue creado por Mark Otto y Jacob Thornton en Twitter en 2011. La idea detrás de Bootstrap era proporcionar un conjunto de herramientas consistentes y reutilizables para diseñadores y desarrolladores, permitiéndoles crear sitios web y aplicaciones con un diseño coherente y moderno.

Desde su lanzamiento, Bootstrap ha evolucionado significativamente, con múltiples versiones que han mejorado su funcionalidad y flexibilidad. La versión 5.3 es la última iteración, que incluye nuevas características y mejoras en el rendimiento.

## Funcionamiento de Bootstrap

Bootstrap se basa en una combinación de HTML, CSS y JavaScript para proporcionar componentes de interfaz de usuario predefinidos y estilos que se pueden utilizar para construir sitios web y aplicaciones. Algunos de los componentes más comunes incluyen:

- **Sistema de rejilla (Grid System):** Permite crear diseños responsivos utilizando una estructura de columnas y filas. Cada fila, estará dividida en 12 columnas.
- **Componentes de UI:** Incluye botones, formularios, tarjetas, modales, y más, que se pueden personalizar fácilmente.
- **Utilidades/Iconos:** Ofrece clases de utilidad para el espaciado, alineación, colores, y otros estilos comunes.

Para empezar a usar Bootstrap, simplemente incluye los archivos CSS y JavaScript en tu proyecto y utiliza las clases y componentes proporcionados para construir tu interfaz de usuario.

## Clases Más Usadas en Bootstrap

### Sistema de Rejilla (Grid System)
- **`.container .container-fluid`**: Contenedor principal que centraliza el contenido y agrega padding horizontal.
    - La clase `.container`, crea un contenedor responsivo con un ancho máximo fijo que depende del tamaño del dispositivo.
     La clase `.container-fluid`, crea un contenedor responsivo que cubre el 100% del ancho de la ventana.
     - Puedes ver un [ejemplo aquí](contenedores.html).
- **`.row`**: Contenedor para columnas, creando una fila en el diseño de la rejilla. Las columnas de los elementos de una fila, deben sumar 12.
- **`.col`**: Define una columna y se puede usar en combinación con tamaños específicos, por ejemplo, `.col-4` para definir una columna que ocupe 4 partes de 12. 
- Dimensiones: 
    - `.col-xs-` Muy pequeño < 576px
    - `.col-sm-` Pequeño  >= 576px
    - `.col-md-` Mediano >= 768px
    - `.col-lg-` Grande >= 992px
    - `.col-xl-` Extra grande >= 1200px
    - `.col-xxl-` Extra extra grande >= 1400px

### Clases de Componentes de UI
- Es un elemento HTML reutilizable que ya viene con un estilo predefinido.
- En el sitio web de [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/), puedes encontrar una lista completa de los componentes disponibles.
- Puedes comprobar la lista de iconos disponibles de [Bootstrap Icons](https://icons.getbootstrap.com/).
- **`.btn`**: Clase base para todos los botones.
  - **`.btn-primary`**: Botón principal, generalmente en color azul.
  - **`.btn-secondary`**: Botón secundario, usualmente en gris.
- **`.navbar`**: Clase para crear una barra de navegación.
  - **`.navbar-light`**: Barra de navegación clara.
  - **`.navbar-dark`**: Barra de navegación oscura.
- **`.card`**: Clase para crear una tarjeta.
  - **`.card-body`**: Contenedor del cuerpo de la tarjeta.
  - **`.card-title`**: Clase para el título de la tarjeta.

### Clases de Utilidades
- **`.m-*`**: Clases para el margen (margin). Ejemplo: `.m-3` añade un margen de 3 unidades.
- **`.p-*`**: Clases para el padding. Ejemplo: `.p-3` añade un padding de 3 unidades.
- **`.text-center`**: Centra el texto.
- **`.text-left`**: Alinea el texto a la izquierda.
- **`.text-right`**: Alinea el texto a la derecha.
- **`.bg-*`**: Clases para el fondo (background). Ejemplo: `.bg-primary` establece el fondo como el color primario.
- **`.d-*`**: Clases de visualización (display). Ejemplo: `.d-flex` para utilizar Flexbox.

### Flexbox
- **Flexbox** es un modelo de diseño que permite a los elementos distribuir el espacio dentro de un contenedor de manera automáticamente y más eficiente y predecible.
- Bootstrap utiliza Flexbox para crear diseños responsivos y flexibles.
- Algunas clases de Flexbox en Bootstrap incluyen:
  - **`.d-flex`**: Activa el modelo de caja flexible.
  - **`.flex-row`**: Establece la dirección del ejeprincipal en fila.
  - **`.flex-column`**: Establece la dirección del ejeprincipal en una columna.
  - **`.justify-content-*`**: Alinea los elementos en el eje principal.
    - **`.justify-content-start`**: Alinea los elementos al principio.
    - **`.justify-content-end`**: Alinea los elementos al final.
    - **`.justify-content-center`**: Alinea los elementos en el centro.
    - **`.justify-content-between`**: Alinea los elementos con espacio entre ellos.
    - **`.justify-content-around`**: Alinea los elementos con espacio alrededor de ellos.
    - **`.justify-content-evenly`**: Alinea los elementos con espacio uniforme entre ellos.
  - **`.align-items-*`**: Alinea los elementos en el eje perpendicular al eje principal.
    - **`.align-items-start`**: Alinea los elementos al principio.
    - **`.align-items-end`**: Alinea los elementos al final.
    - **`.align-items-center`**: Alinea los elementos en el centro.
    - **`.align-items-baseline`**: Alinea los elementos en la línea base.
    - **`.align-items-stretch`**: Estira los elementos para que ocupen todo el espacio disponible.
  - **`.flex-wrap*`**: Determina si los elementos deben envolverse en múltiples líneas.
    - **`.flex-wrap`**: Envuelve los elementos en múltiples líneas.
    - **`.flex-nowrap`**: No envuelve los elementos en múltiples líneas.
    - **`.flex-wrap-reverse`**: Envuelve los elementos en múltiples líneas en orden inverso.