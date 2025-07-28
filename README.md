# Interferometer

This is cheap low tech interferometer I made for CERN
<p align="center">
  <img src="data/interferometer.jpg" width="400" height="200" alt="Interferometer">
</p>

https://cds.cern.ch/record/2705782?ln=en

Here is the record of the interferometer I designed for high school students to learn about complex physics in a really simple way. We managed to get kids creating real quantum effects with £50 worth of equipment and 10 minutes of teaching. It could even measure with the help of a Fourier transform the deflection of a piezo crystal to 50nm. It is now part of the science gateway outreach programs at CERN! If you want the latest design it is up to date here:

https://scoollab.web.cern.ch/laserlab3D

# The self playing piano "Tchaibotsky"

![alt text](https://github.com/matthew-gratin/portfolio/blob/main/piano.jpg)

This is a piano that can compose music by itself and play it too! see if you can tell the difference between human and computer generated and performed art in this turing test:

https://docs.google.com/forms/d/e/1FAIpQLSdsWYuC4zJo1RCfpW2OO7gJrU88cWlsbYe5tWjYFyxj3gjd-g/viewform

I got featured on Tiffany Poon's podcast!

https://www.youtube.com/watch?v=dhRES9lAGE0

From the results of this test I concluded people couldn't tell the difference. This was originally built in the year the Attention is all you need paper came out and popularised transformers, it uses one of the earliest implimentations of one. 
This is built from 88 solenoid actuators. It can generate unlimited unconditioned pieces around 2-3 minutes in length in the form of midi files and can even attempt to harmonise it with your own songs. 

If the google docs doesn't work the music clips are in the repo. Here is a link to my thesis on the first version:

![alt text](https://github.com/matthew-gratin/portfolio/blob/main/Tchaibotsky-2_compressed-1.pdf) 

Version 2 of this with better esd protected PCB circuit boards and aluminium frame and greater controller accuracy will be presented in a lecture at Oxford University in November

# Robot Sister

It was my cousins wedding and my sister had to miss it as she was in New Zealand in the middle of a huge rocket mission. My mission was to build a telepresence robot in 2 weeks to get her to the wedding. I made a 3 omniwheeled robot with camera, microphone and speaker. Made it stream the video feed to a webpage which she could use to ssh into the robot via a virtual local network and then control all the features through the internet. She was able to dance the robot with everyone else and sing along to all the songs (with 1.2 seconds time delay). 
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/darcey%20pre%20party.jpeg?raw=true) 
she got a bit battered during the wedding!
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/darcey%20post%20party.jpeg?raw=true) 

# Wizard Chess

![alt text](https://github.com/matthew-gratin/portfolio/blob/main/chess%20image.jpg)

I love Harry Potter and thought it would be cool to make a the wizards chess in real life with the magic of engineering. You speak the chess commands and the pieces move on their own to the right places, just like in the movie. There are 3 modes, player vs player, player vs computer and my personal favourite is computer vs computer. I coded the AI from scratch using markov decision trees. It only looks two moves ahead and can beats me every time, I don't know what that says about me!
It uses an electromagnet on a 2 axes gantry to move the pieces to the desired locations and connects to a google cloud server to offload the speech recognition system to Google's much bulkier computer than my nuc.  Features I want to develop are web access, so you can play against people online and connect to live chess streams where the wizard chess board would move its pieces as the professional players move theirs.

There are a couple videos in this github of it working, but if you want to interview me I might bring the board to your office for a friendly game ;)

https://github.com/matthew-gratin/portfolio/blob/main/pawn_move.mp4


# The drawing machine. 

I built it from my old 3d printed CNC machine I made. Now I have a proper CNC it had become redundant to own a dremel desktop one. I built a image to SVG to G-code converter that uses Canny edge detection and blob analysis to binarise and fill images in artistic ways automatically and then outputs a gcode that can be sent to the machine.

![alt text](https://github.com/matthew-gratin/portfolio/blob/main/417015412_3267467930212963_5978014354640970526_n.jpg)

It runs off gbrl with some TMC2208 drivers. 
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/417487049_7420312574680181_8911318335456844971_n.mp4)

I wanted to make a painting for my girlfriend's birthday but I have no talent in art as I have no talent other than for image binarisation algorithms and robotics. She was happy!
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/411062386_1005629607648093_974153597133220309_n.jpg)

# Brickify
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/brickfy%20example.png)
http://www.mediafire.com/file/cdr427dj3cs7xna/Brickify-1.0.1.zip/file

This converts normal pictures to lego pictures

This is brickify 1.0.1 Second release with more build features planned if demand is high (however I have done no promotion for this so I doubt it will be a priority until I want to make more lego mosaics myself).

Common colours are colours that regularly have over 1000 bricks on bricklink available. Most colours are still avaiable and don't cost more than 2p so are still viable but will potentially make an awkward order. Greyscale uses new lego grey colours (light grey and dark grey is discontinued)

Note that lego baseplates come in 48x48 and 32x32 configureations.

Dithering uses floyd steinbeck method, just makes them look better. Aspect ratio does the thing you would expect.

Saturation is between -255 and 255 for each colour. it offsets the image deeper or lesser into that hue.

Saving a file also adds a text file to the directory, this contains the bricks you need to create that image and a link where to buy them.

Improvements to make: -add multi brick type generation -heightmap additions -different dithering options -different default methods of hue connection as euler distance rgb counter intuitively doesnt produce the most visually similar colours.

# Nixie tube clock

I have always been a fan of a metric time. That being 10 hours in a day, 100 minutes in an hour and 100 seconds in a minute. However no clocks on the market have this feature, so I had to make one. It has a custom pcb for driving the ocsillator and high voltage tubes. I gave it three modes so it can be used as a boring normal clock too.
![alt text](https://github.com/matthew-gratin/portfolio/blob/main/nixie%20clock.jpeg?raw=true)

# To add to github:

Automatic Chopsticks

Orrery

Drone

# Currently building:

Ultra lightweight robot dog with a capstan drive




