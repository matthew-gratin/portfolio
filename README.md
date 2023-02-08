# portfolio

Wanted to share some of my interactive projects I have done!

This is my super cheap interferometer I made for CERN!
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/interferometer.jpg)
https://cds.cern.ch/record/2705782?ln=en

Here is the record of the interferometer I designed for high school students to learn about complex physics in a really simple way. We managed to get kids performing their own quantum experiments with £50 worth of equipment and 10 minutes of teaching. It is now a big hit on the science gateway/S'cool lab outreach programs at CERN! If you want the latest design it is up to date here:

https://scoollab.web.cern.ch/laserlab3D


Here is Brickify!
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/brickfy%20example.png)
http://www.mediafire.com/file/cdr427dj3cs7xna/Brickify-1.0.1.zip/file

This converts normal pictures to lego pictures

This is brickify 1.0.1 Second release with more build features planned if demand is high (however I have done no premotion for this so I doubt it will be a priority untill I want to make more lego mosaics myself.

Common colours are colours that regularly have over 1000 bricks on bricklink available. Most colours are still avaiable and don't cost more than 2p so are still viable but will potentially make an awkward order. Greyscale uses new lego grey colours (light grey and dark grey is discontinued)

Note that lego baseplates come in 48x48 and 32x32 configureations.

Dithering uses floyd steinbeck method, just makes them look better. Aspect ratio does the thing you would expect.

Saturation is between -255 and 255 for each colour. it offsets the image deeper or lesser into that hue.

Saving a file also adds a text file to the directory, this contains the bricks you need to create that image and a link where to buy them.

Improvements to make: -add multi brick type generation -heightmap additions -different dithering options -different default methods of hue connection as euler distance rgb counter intuitively doesnt produce the most visually similar colours.


This is the self playing piano "Tchaibotsky"

![alt text](https://github.com/matthew-gratin/portfolio/blob/main/piano.jpg)

This is a piano that can compose music by itself and play it too! see if you can tell the difference between human and computer generated and performed art in this turing test:

https://docs.google.com/forms/d/e/1FAIpQLSdsWYuC4zJo1RCfpW2OO7gJrU88cWlsbYe5tWjYFyxj3gjd-g/viewform

From the results of this test I found out people just couldn't tell the difference. What an amazing world we live in!
This is built from 88 solenoid actuators and a simple raspberry pi. It can generate unlimited amounts of music in the form of midi files and can even attempt to harmonise it with your own songs. 

If the google docs doesn't work the music clips are in the repo.

Wizard Chess!

![alt text](https://github.com/matthew-gratin/portfolio/blob/main/chess%20image.jpg)

I love Harry Potter and thought it would be cool to make a the wizards chess in real life with the magic of engineering. You just need to speak the chess commands and the pieces move on their own to the right places, just like in the movie. There are 3 modes, player vs player, player vs computer and my personal favourite is computer vs computer. I coded the AI from scratch using markov decision trees and it was just about good enough to beat me!
It uses an electromagnet on a 2 axes gantry to move the pieces to the desired locations. I am starting a kickstarter for this to be a commercial product as there are several products without the speech USP currently being sold at price I can undercut that have been incredibly successful. Features I want to develop are web access, so you can play against people online and connect to live chess streams where the wizard chess board would move its pieces as the professional players move theirs.

There are a couple videos in this github of it working, but if you want to interview me I might bring the board to your office for a friendly game ;)

https://github.com/matthew-gratin/portfolio/blob/main/pawn_move.mp4


