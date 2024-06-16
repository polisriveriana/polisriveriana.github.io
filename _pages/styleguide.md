---
layout: page
title: Cómo usar este sitio
permalink: /styleguide/
image: 11.jpg
---

Un párrafo se ve así: dolor amet cray stumptown fingerstache neutra food truck seitan poke cardigan waistcoat VHS snackwave celiac hella. Godard seitan shoreditch flexitarian next level trust fund man braid vegan listicle keytar bitters. Disrupt cray fashion axe unicorn lomo shaman poke glossier keffiyeh snackwave austin tattooed seitan hexagon lo-fi. Lumbersexual irony vaporware, butcher shaman church-key iceland.

### Encabezados por defecto:

# H1 Por ejemplo
## H2 Por ejemplo
### H3 Por ejemplo
#### H4 Por ejemplo
##### H5 Por ejemplo
###### H6 Por ejemplo

{% highlight markdown %}
## Encabezado de primer nivel
### Encabezado de segundo nivel
#### Encabezado de tercer nivel
{% endhighlight %}

***

### Listas

#### Ejemplo de lista ordenada:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

***

#### Ejemplo de lista desordenada:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

{% highlight markdown %}
1. Elemento de lista ordenada 1
2. Elemento de lista ordenada 2

* Elemento de lista desordenada 1
* Elemento de lista desordenada 2
{% endhighlight %}

***

### Tabla

<div class="table-container">
  <table>
    <tr><th>Encabezado 1</th><th>Encabezado 2</th><th>Encabezado 3</th><th>Encabezado 4</th><th>Encabezado 5</th></tr>
    <tr><td>Fila:1 Celda:1</td><td>Fila:1 Celda:2</td><td>Fila:1 Celda:3</td><td>Fila:1 Celda:4</td><td>Fila:1 Celda:5</td></tr>
    <tr><td>Fila:2 Celda:1</td><td>Fila:2 Celda:2</td><td>Fila:2 Celda:3</td><td>Fila:2 Celda:4</td><td>Fila:2 Celda:5</td></tr>
    <tr><td>Fila:3 Celda:1</td><td>Fila:3 Celda:2</td><td>Fila:3 Celda:3</td><td>Fila:3 Celda:4</td><td>Fila:3 Celda:5</td></tr>
    <tr><td>Fila:4 Celda:1</td><td>Fila:4 Celda:2</td><td>Fila:4 Celda:3</td><td>Fila:4 Celda:4</td><td>Fila:4 Celda:5</td></tr>
    <tr><td>Fila:5 Celda:1</td><td>Fila:5 Celda:2</td><td>Fila:5 Celda:3</td><td>Fila:5 Celda:4</td><td>Fila:5 Celda:5</td></tr>
    <tr><td>Fila:6 Celda:1</td><td>Fila:6 Celda:2</td><td>Fila:6 Celda:3</td><td>Fila:6 Celda:4</td><td>Fila:6 Celda:5</td></tr>
  </table>
</div>

***

### Citas

#### Una cita se ve así:

> No dejes para mañana lo que puedas hacer pasado mañana igual de bien. — Mark Twain

***

### Resaltador de sintaxis

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

### Imágenes

![]({{site.baseurl}}/img/03.jpg)

***

### Videos

<iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>
