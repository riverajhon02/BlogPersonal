---
layout: post
title:  "Instalando Jekyll Ubuntu"
date:   2020-05-21 23:28:30 -0500
categories: jekyll update
---
Jekyll es un generador de sitio estático. Le da texto escrito en su lenguaje de marcado favorito y utiliza diseños para crear un sitio web estático. Puede ajustar cómo desea que se vean las URL del sitio, qué datos se muestran en el sitio y más.
Para la instalación de Jekyll en Ubuntu debes seguir los **siguientes pasos:**



### Instalar a full Ruby development environment.
Para comenzar a trabajar con éste generador debemos tener instalado [Ruby](https://jekyllrb.com/docs/installation/) en cualquiera de sus versiones

### Instalar Jekyll y su gema
Como bien sabemos las gemas son librerias, en este caso instalaremos la gema de Jekyll
{% highlight ruby %}
gem install jekyll bundler
{% endhighlight %}

### Creación de un nuevo proyecto
Creamos un proyecto para verificar que se halla instalado corectamente, donde **myblog** es el 
nombre del proyecto a crear.
{% highlight ruby %}
  jekyll new myblog
{% endhighlight %}

### Ingresamos a al poryecto creado
Una vez se cree el proyecto nos debemos transladar a el, para ello utilizamos
{% highlight ruby %}
  cd myblog
{% endhighlight %}

### Servidor local
Ya construido el sitio lo colocamos a disposición de un servidor local

{% highlight ruby %}
  bundle exec jekyll serve

{% endhighlight %}

### En su navegador favorito busque [http://localhost:4000](http://localhost:4000)



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
