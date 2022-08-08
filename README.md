# ANATOMIA DE HTML5
Este documento muestra la `anatomía` del código HTML5 y `las partes con su respectivo significado`.
## Antomía simple
A continuación, se muestra la anatomía simple de HTML5:
```bash
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
</body>
</html>
```
# PARTES Y SU SIGNIFICADO
Antes de mencionar las partes y sus significados, entendamos que es `elemento`, `etiqueta` y `atributo`:

**A.** `Elemento:` conforman la suma de etiquetas (etiqueta de apertura y etiqueta de cierre) y el contenido.

**B.** `Etiqueta:` conforman etiquetas de apertura (<...>) y de cierre (</...>), como se puede apreciar la etiqueta de cierre se diferencia con el aumento de slash (/). _(...) representa el nombre de etiqueta, puede ser cualquier otra etiqueta, como: p,h1,h2,h3..._.

**C.** `Atributo:` determinan cierta información de la etiqueta, generalmente va asociado a un valor determinado y se escribe después de la etiqueta, seguido con un signo igual antes del carácter >, como se observa en la `imagen 1`.
![image](https://eliseovega.github.io/imgh/anatomia_atributo.svg)

A continuación, se muestra las etiquetas, elementos y atributos con sus respectivos significados:
- La etiqueta `DOCTYPE` declara el tipo de documento, de esta forma señalamos que este documento es un documento HTML5:
```bash 
<!DOCTYPE html>
```

- El elemento `html` delimita el documento HTML:
```bash 
<html> #.... </html>
```

- El atributo `lang` indica el lenguaje del contenido del código:
```bash 
<!html lang="es"> </html>
```

- El elemento `head` delimita la cabecera del documento:
```bash 
<head> </head>
```

- La etiqueta `meta` sirve para identificar y para mostrar en los buscadores las propiedades del documento como por ejemplo el autor, descripción, título, entre otros:
> La `meta chartset` establece el tipo de comunicación del documento.
```bash
<meta charset="UTF-8">
```

> La siguiente `meta` permite al navegador mostrar las páginas webs, es decir que establece la compatibilidad de vista.
```bash
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

> La siguiente `meta` establece que el documento se mostrará en el tamaño del dispositivo, es decir que se adaptará al tamaño de una computadora, laptop, tablet, celular, entre otros.
```bash
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
- La etiqueta `title` muestra el título de la página web:
```bash
<title>tituloDocumento</title>
```
- El elemento `body` delimita el cuerpo del documento y contiene todo lo que se observa en el navegador. textos, vídeos, imágenes, audios, entre otros:
```bash
<body> </body>
```

- la función `main` es el área principal del contenido, es decir, es el punto de partida para la ejecución del programa:  
```bash
<main> </main>
```

- Especifica la cabecera de la página, generalmente va el título, logo y más:  
```bash
<header> </header>
```

- la etiqueta `nav` delimita el menú de la página, en dónde se coloca enlaces internos para moverse entre las secciones del sitio web:  
```bash
<nav> </nav>
```

## OTRAS ETIQUETAS BÁSICAS
- la etiqueta `href` contiene un link de hoja de estilos externo:  
```bash
    <a href="https://github.com/vladimirsarmiento/Estructura-de HTML5/edit/main/README.md">Anatomia de HTML5</a>
```

- la etiqueta `section` engloba una sección de texto, imágenes y otros elementos que se relacionan entre si:  
```bash
    <section> </section>
```

- otra forma de dividir es con la etiqueta `div` para aplicar clases y modificación de estilos posteriormente:  
```bash
    <div> </div>
```

- La etiqueta `p` sirve para colocar conjunto de textos formando un párrafo:  
```bash
    <p> </p>
```

- La etiqueta `img` sirve para colocar una imagen en el documento mediante un enlace:  
```bash
<img src="https://www.fundacion-affinity.org/sites/default/files/los-10-sonidos-principales-del-perro.jpg" alt="">
```
- Podemos mencionar a otras etiquetas como:
```bash
<!--para una lista: -->
<li> </li>

<!--para una lista que no importe el orden-->
<ul> </ul>

<!--para una lista que si importe el orden-->
<ol> </ol>
```

```bash
<!--Para representar el encabezado de una página, puede ir de 1 al 6: -->
<h1> </h1>
<h2> </h2>
<h3> </h3>
<h4> </h4>
<h5> </h5>
<h6> </h6>
```

Si desea más información sobre las etiquetas de HTML5 ingrese [AQUÍ](https://www.brandominus.com/manuales/manual_html5.pdf)

