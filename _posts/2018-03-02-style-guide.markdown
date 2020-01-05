---
layout: post
title: Style Guide
image: 8.jpg
date: 2018-03-02 13:35:20 +0200
tags:
categories: guide
---
A paragraph looks like this — dolor amet cray stumptown fingerstache neutra food truck seitan poke cardigan waistcoat VHS snackwave celiac hella. Godard seitan shoreditch flexitarian next level trust fund man braid vegan listicle keytar bitters. Disrupt cray fashion axe unicorn lomo shaman poke glossier keffiyeh snackwave austin tattooed seitan hexagon lo-fi. Lumbersexual irony vaporware, butcher shaman church-key iceland.

***

#### Headings by default:

# H1 For example

<script src="https://github.com/snp600/snp600.github.io/blob/master/js/zoom-D.js"></script>
<style>
 .zoomD {
         width: 800px;
        height: auto;
  cursor: pointer;
}

#lb-back {
  position: fixed;
  //margin-top: 10%;
  //margin-left: 10%;
  width: 80%;
  height: auto;
  //height: 100vh;
  background: rgba(0, 0, 0, 0.5);
  z-index: 999;
  visibility: hidden;
  opacity: 0;
  transition: all 0.4s;
}
#lb-back.show {
  visibility: visible;
  opacity: 1;
}
#lb-img {
  text-align: center;
}

</style>


<div id="lb-back">
    <div id="lb-img"></div>
</div>



## H2 For example
<img src="https://i.imgur.com/Hfpe5BJ.jpg" class="zoomD"/>
### H3 For example

<script src="https://github.com/snp600/snp600.github.io/blob/master/js/tst.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<img data-enlargable style="cursor: zoom-in; transition: all 0.4s; width: 800px;
        height: auto;" src="https://i.imgur.com/Hfpe5BJ.jpg" />

#### H4 For example

<style>
      .fullscreen:-webkit-full-screen {
      width: auto !important;
      height: auto !important;
      margin:auto !important;
  }
     .fullscreen:-moz-full-screen {
      width: auto !important;
      height: auto !important;
      margin:auto !important;
  }
     .fullscreen:-ms-fullscreen {
      width: auto !important;
      height: auto !important;
      margin:auto !important;
  }     
     </style>

<img id="theImage" class="fullscreen" style="width: 800px;
        height: auto;" src="https://i.imgur.com/Hfpe5BJ.jpg" onClick="makeFullScreen()"> 

<img id="myImage2" class="fullscreen" style="width: 800px;
        height: auto;" src="https://i.imgur.com/Hfpe5BJ.jpg" onClick="makeFullScreen2()"> 

##### H5 For example

<style>
      .zoomA {
        width: 800px;
        height: auto;
        transition-duration: 1s;
        transition-timing-function: ease;
      }
      .zoomA:hover {
        transform: scale(1.3);
      }
</style>


<img src="https://i.imgur.com/Hfpe5BJ.jpg" class="zoomA"/>

###### H6 For example

{% highlight markdown %}
## Heading first level
### Heading second level
#### Heading third level
{% endhighlight %}

***

#### Lists

###### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

###### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

{% highlight markdown %}
1. Order list item 1
2. Order list item 1

* Unordered list item 1
* Unordered list item 2
{% endhighlight %}

***

#### Quotes

###### A quote looks like this:

> Never put off till tomorrow what may be done day after tomorrow just as well. — Mark Twain

***

#### Syntax Highlighter

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

#### Images

![]({{site.baseurl}}/images/2.jpg)

***

#### Videos

###### Youtube

<iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>
