# portfolio

Wanted to share some of my interactive projects I have done!

https://cds.cern.ch/record/2705782?ln=en
Here is the record of the interferometer I designed for high school students to learn about complex physics in a really simple way. We managed to get kids performing their own quantum experiments with £50 worth of equipment and 10 minutes of teaching. It is now a big hit on the science gateway/S'cool lab outreach programs at CERN! If you want the latest design it is up to date here:
https://scoollab.web.cern.ch/laserlab3D

http://www.mediafire.com/file/cdr427dj3cs7xna/Brickify-1.0.1.zip/file
Here is Brickify!
This converts normal pictures to lego pictures

This is brickify 1.0.1 Second release with more build features planned if demand is high (however I have done no premotion for this so I doubt it will be a priority untill I want to make more lego mosaics myself.

Common colours are colours that regularly have over 1000 bricks on bricklink available. Most colours are still avaiable and don't cost more than 2p so are still viable but will potentially make an awkward order. Greyscale uses new lego grey colours (light grey and dark grey is discontinued)

Note that lego baseplates come in 48x48 and 32x32 configureations.

Dithering uses floyd steinbeck method, just makes them look better. Aspect ratio does the thing you would expect.

Saturation is between -255 and 255 for each colour. it offsets the image deeper or lesser into that hue.

Saving a file also adds a text file to the directory, this contains the bricks you need to create that image and a link where to buy them.

Improvements to make: -add multi brick type generation -heightmap additions -different dithering options -different default methods of hue connection as euler distance rgb counter intuitively doesnt produce the most visually similar colours.


