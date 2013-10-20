# Fotorama for Bower

This is packager, that allows you to simply install and maintain [Fotorama](http://fotorama.io/) via [Bower](http://bower.io/).

## Set-up

1. Install the package:

    ```bash
    bower install fotorama
    ```

2. Use it in HTML:

    ```html
    <!-- 1. Link to jQuery (1.8 or later), -->
    <script src="/bower_components/jquery/jquery.js"></script>

    <!-- fotorama.css & fotorama.js. -->
    <link  href="/bower_components/fotorama/fotorama.css" rel="stylesheet">
    <script src="/bower_components/fotorama/fotorama.js"></script>

    <!-- 2. Add images to <div class="fotorama"></div>. -->
    <div class="fotorama">
      <img src="1.jpg">
      <img src="2.jpg">
    </div>

    <!-- 3. Enjoy! -->
    ```