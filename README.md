

För att skapa lower thirds:

`` convert -verbose -density 300 lower_thirds_2024.pdf -quality 100 -resize 1920x1080 -transparent white lower_thirds.png ``

Eller om de ska ha en lila "chroma-key":

`` convert -verbose -density 1600 lower_thirds_2024.pdf -quality 400 -fuzz 5% -transparent \#7f007f -resize 1920x1800 lower_thirds.png ``



De andra slidsen gjorde jag med:

`` convert -verbose -density 300 video-presentation2.pdf -quality 100 -resize 1920x1080 slides2.png `` 


Eventuellt sätta ihop flera PDF:er först med:
``pdftk long_names.pdf lower_thirds_mattekollo_2024.pdf output lower_thirds_2024.pdf`` 