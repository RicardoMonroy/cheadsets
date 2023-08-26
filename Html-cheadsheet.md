# Mi hoja de trucos de HTML

Estructura básica de HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

## Componentes del Head

```
<head>
    <title>Document</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style type="text/css">
        /* CSS code */
    </style>
    <script src="script.js"></script>
    <script>
        // JavaScript Code
    </script>
    <meta mane="keywords" content="keywords">
    <meta name="author" content="name">
    <meta name="description" content="description">
</head>
```

## Componentes del Body

Cabeceras

```
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
<h6>Título 6</h6>
```

Párrafos

```
<p>Párrafo</p>
<span>Párrafo</span>
```

Formato

```
<p>Este <em>párrafo</em> es <strong>importante</strong>!</p>
<p>Esta es una formula: (a+b)<sup>2</sup> + b<sup>2</sup>.</p>
```

Citas

```
<p><cite>Este libro</cite> es una referencia a un autor</p>
<q cite="url">referencia</q>
    <blockquote cite="url">Contenido</blockquote>
```

Links

```
<a href="https://tecmilenio.mx">Tecmilenio</a>
```

Imágenes

```
<img src="image.jpg" alt="descripción" width="300" height="200">
```

Bloques

```
<div>bloque</div>
<span>inline</span>
```

Listas

```
<ul>
    <li>Lista 1</li>
    <li>Lista 2</li>
    <li>Lista 3</li>
</ul>
<ol>
    <li>Lista 1</li>
    <li>Lista 2</li>
    <li>Lista 3</li>
</ol>
<ol type="a">
    <li>Lista 1</li>
    <li>Lista 2</li>
    <li>Lista 3</li>
</ol>
```

Tablas

```
<table>
    <tr>
        <th>heading 1</th>
        <th>heading 2</th>
        <th>heading 3</th>
    </tr>
    <tr>
        <td>line</td>
        <td>line</td>
        <td>line</td>
    </tr>
    <tr>
        <td>line</td>
        <td>line</td>
        <td>line</td>
    </tr>
</table>
```

Formularios

```
<form action="url">
    <fieldset>
        <legend>Identificate</legend>
        <label for="username">Nombre de usuario: </label>
        <input type="text" name="username">
        <label for="password">Password: </label>
        <input type="password" name="password">
        <label for="email">Email de usuario: </label>
        <input type="email" name="email">
        <input type="checkbox" name="" id="">
        <input type="datetime" name="" id="">
        <input type="radio" name="" id="">
        <input type="number" name="" id="">
        <textarea name="" id="" cols="30" rows="10"></textarea>
        <input type="button" value="">
    </fieldset>
</form>
```
