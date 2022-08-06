# ANATOMIA DE HTML5
Este documento muestra la `anatomía` del código HTML5 y `las partes con su significado` de la etiqueta y atributo.
## Antomía simple
A continuación se muestra la anatomía simple de HTML5:
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

**A.** `Elemento:` conforman la suma de etiquetas (etiqueta de apertura, etiqueta de cierre) y el contenido.

**B.** `Etiqueta:` conforman etiquetas de apertura <...> y de cierre </...>, como se puede apreciar la etiqueta de cierre se diferencia con el slash (/). _..., representa el nombre de etiqueta, puede ser cualquier otra etiqueta, como: p,h1,h2,h3..._

**C.** `Atributo:`

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
