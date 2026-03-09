# README – Semana Cultural Zaragoza 2025

## 1. Descripción del proyecto
Este proyecto es una página web simple hecha con HTML y Bootstrap.  
La página muestra información sobre la Semana Cultural Zaragoza 2025.

En la página aparecen:
- El título del evento
- La fecha
- Información del evento
- Las actividades
- Un pie de página con contacto

Bootstrap se usa para que la página tenga un diseño ordenado y se vea bien en diferentes pantallas.

## 2. Secciones usadas con su número de columnas de Bootstrap

Navbar  
Barra superior con el nombre del evento.  
No usa columnas.
Header  
Imagen grande con el título del evento y la fecha.  
No usa columnas.
Información  
Texto que explica el evento y una lista con datos importantes.  
No usa columnas.
Actividades  
Se usa un row de Bootstrap.  
Dentro hay 3 columnas (col-md-4).  
Cada columna tiene:
- una imagen
- un título
- un texto corto.

Footer  
Pie de página con el nombre del evento y el email.  
No usa columnas.

## 3. Componentes prediseñados de Bootstrap usados

En el proyecto se usan estos componentes de Bootstrap:

- Navbar (barra superior)
- Container (para centrar el contenido)
- Row (fila para organizar columnas)
- Col-md-4 (tres columnas iguales)
- Img-fluid (para que las imágenes se adapten)

También se usan algunas clases de Bootstrap:

- bg-dark
- text-white
- mt-4
- p-3

## 4. Descripción de los commits y mejoras

Commit 1 – Estructura básica  
Se creó el archivo HTML y la estructura básica de la página.

Commit 2 – Añadir Bootstrap  
Se añadió el enlace de Bootstrap y se usó container para organizar el contenido.

Commit 3 – Crear el header  
Se añadió una imagen de fondo y el título del evento con la fecha.

Commit 4 – Añadir sección de información  
Se añadió un texto explicando el evento y una lista con fecha, lugar y precio.

Commit 5 – Crear sección de actividades  
Se usó row y col-md-4 para hacer tres columnas con imágenes y texto.

Commit 6 – Añadir footer  
Se añadió un pie de página con el nombre del evento y el email.

## 5. Mayor dificultad encontrada y solución
La mayor dificultad fue colocar las actividades en tres columnas.
Para solucionarlo se usó el sistema grid de Bootstrap:
- row para crear la fila
- col-md-4 para dividir el espacio en tres partes iguales
También se usó img-fluid para que las imágenes se ajusten al tamaño de la columna.
