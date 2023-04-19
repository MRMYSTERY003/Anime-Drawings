# Anime-Drawings

Hi there, If you have been following me in youtube you know what these files are, and if you don't know let me explain you

## what is sketchpy

Sketchpy is a Python module for animating drawings of images. The sketchpy module is created on top of the turtle module in Python.

<div align = 'center' style = "display: flex; justify-content: space-between;"> 
<img src = "https://user-images.githubusercontent.com/80098044/154793329-e8ec9635-b49e-4898-8a3e-6462645d6c8c.gif" height = 180 width = 214>
<img src = "https://user-images.githubusercontent.com/80098044/154793382-6d012c24-adbf-4c5a-bd51-b5095a34e9fe.gif" height = 180 width = 214>
</div>

To install sketchpy on your computer, you can go to your command prompt (command line) and run the following command.

```pip install sketchpy==0.0.1```

if you want to know more about the package check this [link](https://github.com/MRMYSTERY003/sketchpy)

## What are these files

The files which are available in this repo are the images which i have drawn which you can find in my [youtube channel](https://www.youtube.com/c/codehub03)

you can use the following code to run the program

```
from sketchpy import canvas

obj = canvas.color_sketch_from_svg(" PATH FOR SVG FILE")
obj.draw()
```

replace the path of the svg file that you need to draw

or you can also use the following code 

```
from sketchpy import canvas

obj = canvas.color_sketch_from_svg(None)
obj.draw(file = 'PATH FOR NPY FILE')
```

