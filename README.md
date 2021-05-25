<a name="first"></a>
# HTML_basics <b></></b>

En este repositorio de github encontraras todos los pasos para poder crear tu propia web paso a paso con html.

* [<img src="https://i.ibb.co/59rQVZc/Folder-Icon.png" height="1.5%" width="1.5%"><img> Head](#head)
  * [<img src="https://i.ibb.co/8N870jW/Web-Icon.png" height="1.5%" width="1.5%"><img> Titulo de la pagina web](#title)
  * [<img src="https://i.ibb.co/GFr8gSn/Icon.png" height="1.5%" width="1.5%"><img> Icono de la pagina web](#icon)
  * [<img src="https://i.ibb.co/JKGRSWM/Animated-Icon.gif" height="1.5%" width="1.5%"><img> Icono animado de la pagina web](#ani-icon)
  * [<img src="https://i.ibb.co/MpdwJjp/Style.png" height="1%" width="1.5%"><img> Conexión con el estilo](#style)
 
* Body
<br></br>
<a name="head"></a>
## Head del html
El head de las paginas web html es el metadato de la pagina web, hay podras escribir el [titulo](#title) que se vera en la barra superior de pestañas web abiertas en tu navegador, tambien bastante importante, podras poner el [icono](#icon) a tu pagina. 
 
Para poder poner en ese apartados las cosas <b>normalmente</b> se usa el atributo <meta> excepto exepciones como el titulo, icono, stilos, ..., por ejemplo mira este cuadro de texto con parte de un <head>:
 

 ```html
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>JEDG</title>
	<meta name="description" content="Descripción que aparecera en los buscadores">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="css/main.css">
	<link rel="stylesheet" href="css/menu.css">
	<link rel="shortcut icon" href="./favicon.png">
</head>
 ``` 
 
 <p align="center">
  <a href="#first"><img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img> Volver arriba <img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img></a>
</p>
<br></br>

<a name="title"></a>
### ___Titulo de la pagina web HTML___

El titulo es una cosa bastante importante de una pagina web, porque sirbe para ser unica entre millones, para poder distinguirte entre todas las pestañas abiertas en tu navegador y poder usarlo como palabras claves para los buscadores como google, bing, duckduckgo, ...

Tambien junto a la [descripción](#descr) podras fijarte de los primeros de los buscadores. Aqui tienes el codigo de ejemplo:

```html
<head>
	<title>Aqui colocas el titulo</title>
</head>
```
 <p align="center">
  <a href="#first"><img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img> Volver arriba <img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img></a>
</p>
<br></br>

<a name="icon"></a>
### ___Icono de la pagina web HTML___
El icono de la pagina web es la segunda cosa más importante aparte del [titulo](#title) para distinguir tu página web de otras entre todas las pestañas abiertas en tu navegador.

Dentro del <link> del [<head>](#head) en el src tendrias que poner el directorio donde tienes almacenado el icono de la pagina web, puede ser en cualquier formato de imagen (.PNG, .ICO, .SVG, .JPEG, ...) y en el atributo <b>rel</b> tendrias que poner a que te quieres dirigir en este caso tendriamos que poner ```shortcut icon```. El tamaño recomendado para el icono de la web es <b>250px X 250px</b>, es decir un logotipo preferiblemente cuadrado.

Aqui tienes una parte del codigo:

```html
<head>
	<link rel="shortcut icon" href="Directorio del icono">
</head>
```

 <p align="center">
  <a href="#first"><img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img> Volver arriba <img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img></a>
</p>

<br></br>
<a name="ani-icon"></a>
### ___Icono animado de la pagina web HTML___
El icono de la pagina web animado es representativo y bastante bonito. No es muy usado por los usuarios porque no estamos acostubrados a ello. 

Dentro del <link> del [<head>](#head) en el src tendrias que poner el directorio donde tienes almacenado el icono de la pagina web, puede ser en cualquier formato de imagen animado(.APNG, .GIF, ...) y en el atributo <b>rel</b> tendrias que poner a que te quieres dirigir en este caso tendriamos que poner ```shortcut icon```. El tamaño recomendado para el icono de la web es <b>250px X 250px</b>, es decir un logotipo preferiblemente cuadrado.

Aqui tienes una parte del codigo:

```html
<head>
	<link rel="shortcut icon" href="Directorio del icono.gif">
</head>
```

 <p align="center">
  <a href="#first"><img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img> Volver arriba <img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img></a>
</p>

<br></br>
<a name="style"></a>
### ___Conexión con el estilo de la web (ccs)___
El estilo de la web es un archivo o apartado del html que da el diseño a la web.

Para ponerlo es muy sencillo, unicamente se necesita una linea de codigo que se tiene que añadir en el apartado del <head>. Que se añade el enlace o el directorio del archivo css en el equipo. Por ejemplo: ./css/main.css

Aqui tienes una parte del codigo:

```html
<head>
	<link rel="stylesheet" href="directorio del css">
</head>
```

 <p align="center">
  <a href="#first"><img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img> Volver arriba <img src="https://i.ibb.co/28kFTyD/Top-Arrow-Icon.png" height="1.5%" width="1.5%"><img></a>
</p>

### Vectores usados:
<p><a href='https://www.freepik.es/vectores/flecha'>Vector de Flecha creado por macrovector - www.freepik.es</a></p>
<p><a href='https://www.freepik.es/vectores/calendario'>Vector de Calendario creado por makyzz - www.freepik.es</a></p>
<p><a href='https://www.freepik.es/vectores/flecha'>Vector de Flecha creado por pch.vector - www.freepik.es</a></p>
