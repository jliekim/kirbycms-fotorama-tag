# KyrbyCMS Fotorama tag extension

KirbyText tag extension for using Fotorama gallery.
Tested on KirbyCMS 2.3.0.
Feel free to use, fork, update, improve.

## Code Example

    (fotorama: first.jpg, second.jpg width:100%)

You can use almost all Fotorama attributes in this way:

    (fotorama: first.jpg, second.jpg width:100% height:100%)

For the full list of attributes refer to [Fotorama website](http://fotorama.io/).

## Installation

Copy the file to the `site/tags` folder.

Add this code to your header file (CDN `js` and `css` for Fotorama):

    <script type="text/javascript" src="http://cdnjs.cloudflare.com/ajax/libs/fotorama/4.6.4/fotorama.js"></script> <!-- 16 KB -->
    <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/fotorama/4.6.4/fotorama.css"> <!-- 3 KB -->

If you prefer you can download Fotorama from it's [website](http://fotorama.io/) and link the `js` and the `css` in your header.
