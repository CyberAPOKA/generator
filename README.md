# generator
## This project takes a group of images and superimposes them on top of each other, you can use them to create all kinds of patterned images.
You can download the project or use the command
``` https://github.com/CyberAPOKA/generator.git ```,
then open the project in your editor and type the following commands in the terminal,
``` npm install ``` and then ``` npm run build ```, 
the system will start creating 100 different images from the predefined ones in the system in the build/images folder
##
## Using the system
Amount of DNA's: To change the amount of DNA's created go to the src/config.js file, on line 13 in growEditionSizeTo: 100, and change it to the amount you want.
##
Exchanging images: To change the images go to the src/config.js file on line 14 in layersOrder,
here you will place them in order from top to bottom defining the overlay, the name of the folders that your images are inside the layers folder.
##
ODDS image: You can define different chances of building each DNA, 
for this you save the image name with # and the chance number you want,
example: AlienHead#25, this image will have a 25% chance of being chosen for each DNA.
