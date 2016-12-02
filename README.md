# ImageHover3

[Demostración](http://zkreations.github.io/ImageHover3/). Icono por [Freepik](http://www.freepik.com)

## Instalación

[Descargar](https://github.com/zkreations/ImageHover3/archive/master.zip) e incluir arriba de `</head>` el codigo css.

```html
<link rel="stylesheet" href="image-hover3.min.css"/>
```

Tambien tienes la opcion de extraer el codigo del efecto que necesites desde `image-hover3.css` (la version sin comprimir).

### Utilizar Image Hover

Solo tienes que agregar un contenedor para la imagen (recomiendo `<a href=""></a>`), y agregar la class **ihover [efecto]**, reemplazando [efecto] por uno de los preestablecidos: 

* `gum`
* `rippleOut`
* `rippleIn`
* `dborder`
* `sliderUp`
* `sliderDown`
* `sliderLeft`
* `sliderRight`

Ejemplo:

```html
<a class="ihover [efecto]" href="#pageUrl"><img src="img/img-01.jpg"/></a>
```

## Limitaciones

* No puedes agregar un grupo de imagenes dentro de un contenedor, cada imagen requiere un contenedor independiente.