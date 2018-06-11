# Lego Vincent Van Gogh Starry Night

This is a short python program, "Starry Night - Recolouring using Lab vs RGB Approximation", that replaces the pixels of an image with the closest matching colour listed as pixels in a colour image.

Recolouring was done on the full (see "Full Sized Images" folder) and reduced size image (see "Resized 116x92 pixels" folder) of the Vincent Van Gogh's Starry Night. I used the image editor Paint.NET to resize the image to 116 by 92 pixels, the number of Lego studs, height and width, of the mosaic I hope to build.

The full image recolouring was done to determine the best colour model to approximate the original pixels in the available Lego colours. The recoloured images can also be found in the "Full Sized Images" folder. I preferred the Lab approximation myself. A link to a short explanation of colour models is included at the end.

The possible Lego colours used to convert the images are stored as different pixel values in the "LegoColoursFull" and "LegoColoursReduced" images (see "Resized 116x92 pixels" folder).
In the "LegoColoursReduced" image all the purples, reds, browns and orange were removed, leaving only the greys, blues and bright yellow. I thought this produced a better result.

The recolouring was then done on the resized 116x92 pixel image and also the image with a 5, 10, 15 and 20 percent increase in both contract and brightness (see "Resized 116x92 pixels" folder then either "*** Colour Scheme" folders). This increased the number of brighter colours, i.e. white and light grey, in the recoloured versions.

I thought the reduced colour and brightness and contrast increase by 5 percent image was the best image and I took it as the base image to which I copy and pasted sections from the other images I preferred. I then manually edited a few bits here and there myself to produce the final image, "Final 116x92 pixel Recoloured Starry Night".

Useful links / Resources I used
* Ed Hall's Starry Night Lego Mosaic http://www.brillig.com/lego/starry_night/ 
* List of stud colours available https://shop.lego.com/en-IE/Pick-a-Brick (enter 3005 in the "Design ID" "Advanced Search" box)
* Explanation of colour difference https://sensing.konicaminolta.us/blog/identifying-color-differences-using-l-a-b-or-l-c-h-coordinates/ 
* Different colour models http://www.colorbasics.com/ColorSpace/ 
* More info in the exact colour of Lego bricks http://www.bartneck.de/2016/09/09/the-curious-case-of-lego-colors/ (Though this was interesting, I scrapped it and just saved the brick images from the official Lego website and used the colour picker tool in Paint.NET to find the RGB values for each colour)

Hope this is of use to someone out there :)
