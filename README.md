Imgage-to-3D-map-.stl-
======================

This is a processing code, to create a 3D printable 3D map out of an image, using the mouse position and the darkness or brigthness of an pixel. It uses Processing 2.x.x.


--Readme--

Hi, I wrote this code, to create 3D maps from normal images. The program uses the bright/darkness of a pixel and the mouse position ( X ) to create a 3D map. the resolution can be changed by using the + and - key on your keyboard. When you press i , it will invert the image/3D effect. Press h to get help ( in the console ) and s to safe a .stl and a .jpg file.

Your input file has to be declared as "input.jpg" and should have a smaller resolution then your desktop (otherwise its hard to control it and the files get too big).

Controls:

    + / -  change resolution
    i      invert image/effect
    s      save a .stl and .jpg
    h      help


intput file:

    "input.jpg"

library(s):

    nervoussystem.obj

warning:

    it may creates some very huge files
    if you press a key, the funktion will happen, it may take time
    the fps go down by increasing the resolution
    it runns on Java
    (╯°□°）╯︵ ┻━┻

test images:

    http://img5.fotos-hochladen.net/uploads/input2ilqvd5zwc.jpg

Optimal Blender settings ( to print it ):

    Rotate it, that it lays down
    move to 0,0,0
    set prescaler to 0.2
    export as .stl
    
