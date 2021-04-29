<a name="first"></a>
# HTML_basics     <img src="https://i.ibb.co/qJpLW79/mi-logo-1.png" height="4%" width="4%" ><img>

En este repositorio de github encontraras todos los pasos para poder crear tu propia web paso a paso con html y css.

* Head
  * [<img src="https://i.ibb.co/8N870jW/Recurso-2-3x.png" height="1.5%" width="1.5%"><img> Titulo de la pagina web](#title)
  * [<img src="https://i.ibb.co/GFr8gSn/Recurso-4-3x.png" height="1.5%" width="1.5%"><img>Icono de la pagina web](#icon)
  * [<img src="https://i.ibb.co/JKGRSWM/Comp-1.gif" height="1.5%" width="1.5%"><img>Icono animado de la pagina web](#ani-icon)
 
* Body

## Head del html
El head de las paginas web html es el matadato de la pagina web, hay podras escribir el [Titulo](#title) que se vera en la barra superior de pestañas web abiertas en tu navegador, tambien bastante importante, podras poner el [icono](#icon) a tu pagina. 
 
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
 
<a name="title"></a>
### ___Titulo de la pagina web HTML___


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 



Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 



Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 

[Volver arriba](#first)
<a name="icon"></a>
## ___Icono de la pagina web HTML___


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 



Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 



Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 

[Volver arriba](#first)
<a name="ani-icon"></a>
## ___Icono animado de la pagina web HTML___


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 



Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 



Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum cursus urna semper, faucibus elit ac, blandit lectus. Suspendisse potenti. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nulla ante dui, maximus ac nulla at, facilisis dapibus sem. Mauris urna magna, faucibus in lectus sit amet, posuere consectetur tortor. Duis suscipit varius magna vel imperdiet. Mauris facilisis odio vitae lacus consequat, aliquam ultrices sapien vulputate. Nullam tincidunt efficitur sollicitudin. Suspendisse lobortis, ligula a auctor gravida, quam felis egestas mi, eu ornare mi mi vitae eros. Nunc feugiat ex in dolor varius, at euismod dolor eleifend. Phasellus nec semper leo. Nullam ex diam, blandit vestibulum volutpat at, pellentesque eget orci. Praesent auctor neque in metus blandit ultricies. Curabitur eget porta mauris.

Vivamus pretium ultricies quam placerat auctor. Nullam at ipsum dapibus, facilisis erat eu, consectetur metus. Nam consequat dictum eros, ac mollis risus elementum vitae. Vestibulum maximus, sapien a lacinia pretium, metus quam pharetra sapien, vel feugiat libero leo nec elit. Curabitur vitae ultrices odio. Nullam in pharetra massa, sed pellentesque metus. Sed egestas venenatis convallis. Sed volutpat nisi sed quam semper feugiat. Vestibulum non dignissim quam. Curabitur nibh quam, vehicula at nisl sed, fringilla porta justo. Praesent malesuada arcu at dapibus pulvinar. 

[Go To TOP](#first)  


### Vectores usados:
<a href='https://www.freepik.es/vectores/flecha'>Vector de Flecha creado por macrovector - www.freepik.es</a>
