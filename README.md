A simple phenakistoscope (https://en.wikipedia.org/wiki/Phenakistoscope) implemented using HTML/CSS and a bit of vanila JS.

http://alexp11223.github.io/Phenakistoscope/Phenakistoscope.html

![](http://i.imgur.com/3iUBZG4.png)

The galloping horse images are from http://opengameart.org/content/galloping-horse (based on photographs by [Eadweard Muybridge, 1878](https://en.wikipedia.org/wiki/Sallie_Gardner_at_a_Gallop)).

`transform: rotate` is used to rotate the image and the rotation degree gets updated via `requestAnimationFrame`. Speed can be changed using controls on the page.

Semi-transparent overlay/mask on top of the image is created using 'svg'.

Should work in all modern browsers (Chrome, FF, ...) and IE 10+.

image_src folder contains Paint.Net image project file with layers, and .psd exported via Paint.Net plugin.
