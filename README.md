# Documentacion-bootstrap

En este repositorio ire colocando mi aprendizaje con este framework tan popular.

## Indice

- [Introduccion](#introduccion)
- [Seccion customize](#seccion-customize)

### Introduccion

Es un famrework muy conocido y utilizado para poder agilizar la creacion de paginas web de forma rapida y responsiva.

### Seccion customize

Es una guia para poder configurar las variables, colores y tipografias.

Las carpetas las trabaja con Sass y para utilizar las variantes debemos de trabajar con Sass.

Eso si, evitar modificar los archivos Bootstrap. Es mejor tener una propia carpeta para cualquier cambio.

Esto es porque, si hay actualizaciones, el fwork lo que hara es planchar esos cambios

### Seccion Layout

- Breakpoints: Son los puntos de distribucion para poder cambiar la maquetacion.

Existe 6 breakpoints por defecto y que es importante saber:

```bash
    - Extra small       | none
    - Small             | sm
    - Medium            | md
    - Large             | lg
    - Extra large       | xl
    - Extra extra large | xxl
```

- Container: En bootstrap es util para definir el espacio entre la izquierda y derecha. Es el tendra las filas y columnas.

### Grid System

El sistema de maquetacion consta de 12 columnas, y dentro de ellas se distribuye el contenido. La mayoria de los frameworks usan este sistema.

La grid de bootstrap esta creada con flex-box. Esto ocasiona por defecto que todos compartan el mismo ancho repartido en toda la ventana.

Si quieres modificar el tamaño de los elementos que estan en una sola fila tambien ofrece tamaño.

- Clases
  - row: Establece que sera una fila
  - col-: Sirve para especificar el numero de columnas
  - col-(sm,md,lg,xl,xxl): Sirve para especificar el tamaño de las columnas.

### Gutters

Es el espaciado que podemos tener entre las columnas, algo asi como la funcion del gap.

### Seccion content

Tiene que ver con el reebot o el reinicio de algunos elementos HTML.

Podemos configurar el tamaño de los encabezados.

### Seccion formularios

Nos detalla los elementos de formulario, hasta las validaciones

### Seccion componentes

Es una lista de todos los elementos visuales que presenta bootstrap y que podemos reutilizar.

### Arquitectura CSS

Este orden se considera buenas practicas

- custom properties: variables personalizadas
- reset style: Para resetear etiquetas
- bootstrap style: Para modificar elementos del framework
- My styles: Es donde iria tus estilos CSS
