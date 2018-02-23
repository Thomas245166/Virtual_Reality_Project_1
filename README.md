# Project 1 VR 4331-001

Thomas Sanchez

All rights reserved

See video walkthrough here: https://youtu.be/3IT3-mnqayo

See demo example here: http://thomas245166.github.io

## Interactables

![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Shelf.JPG)

On the shelf located to the right of the living room are two shelves filled with models from games/movies/animals that I
personally enjoy. Each object located there will is able to play a sound that relates to the model.

#### Phonograph
This object plays the sound of a record scratching when clicked on.

#### Pipboy
When clicked on it will play the level up sound from Fallout: New Vegas.

#### Nintendo Switch
Plays the iconic noise present in all their current commericals.

#### UFO
Plays the X files theme for spooky effects

#### Squid
This is one of my favorite animals, it will play the Blooper noise from 
New Super Mario Bros Wii

#### Planet Express Ship
Plays the "Welcome to the World of Tomorrow" line from the first episode of the Futurama
series

#### Link
Will play the sound of Link falling and screaming from the Legend of Zelda: Wind 
Waker

#### Overwatch Loot Box
This will play the voice from one of the characters (Lucio), the voice line
is "Speed Boost!"

#### R2D2
Clicking on him will make him beep happily

#### Pokeball
Plays the sound from the game of the pokeball closing/opening

#### Star Destoryer
No star destroyer can be complete with a Darth Vader Voice line. Will say "You should have not
returned" when clicked

#### Triceratops
My favorite dinosaur that will let out a mighty roar when clicked.

#### Robot
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/robot.JPG)
This little guy is charge of my server room, here he uses Morse code to communicate,
Click on him to hear what he has to say

#### Like Buttons
Underneath every picture of the Roommate of the Month is a Blue button, when clicked
it will play a firework sound because everyday is a party with my cat, Gregory.

## Dynamic Models

#### Ceiling Fan
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/CeilingFan.JPG)

Upon entering the VR enviroment, the ceiling in the living room will start spinning

#### R2D2
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/R2.JPG)

This little guy has so much excitement he is literally spinning in circles

#### Like Button
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Roommateofthemonth.JPG)

Upon viewing the blue like buttons, each one will increase in size as a visual 
representation of an clickable object.

#### Fire
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Fire.JPG)

The fire in the fireplace will move up and down slowly, nice for chilly winter nights

## Static Models


#### Bathroom
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Bathroom.JPG)
Inside here is a single object which fully furnishes a bathroom complete with
a bath tub, toliet, sink and mirror.


#### Kitchen
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Kitchen.JPG)
Similar to the Bathroom, the kitchen is single ojbect whichs contains every thing
modern kitchen needs, including: Stove, fridge, dinning table and windows


#### Living room
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Livingroom.JPG)
This area has a fire place, sofa, recliner and a coffee table, not to mention the floor
to ceiling HDTV 


#### Bedroom
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Bedroom.JPG)
In here I have a desk with a computer, a wizards table to practice the arcane arts, and my
closet and also some candles and books


#### Hidden Server Room
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/HiddenServerRoom.JPG)
In here is where my smart house's brain lives, I have three server racks and a
robot to help monitor all activity


#### Garage
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Garage.JPG)
In here are a few vehicles I like, there is a moped for quick escapes and a war 
tank in the event I need more firepower, with a garage door for entry and in the back corner is a wood chopping area 
complete with camping gear


#### Laundry Room
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Laundry.JPG)
In here I have a basic washer and drying along with some tools like a drill and paper towels
as well as a small box shelf outside the room containing some small toys.


#### Foyer
![alt text](https://github.com/Thomas245166/Thomas245166.github.io/blob/master/screenshots/Foyer.JPG)
This is the main room of the house, it contains the Roommate of the Month frames as well as my
wet bar for entertaining guests, just be sure not to trip over the rug while dancing


# Help Menu

Movement is handled by the wasd keys on computers with a left mouse click to interact with models.
For mobile devices users, movement is done by tapping and holding the screen, tapping is also used to interact
with the models


# Original Issues

While designing the VR space using the visual inspector, I would copy the entities using the built in button in the
web inspector. Doing this however would cause some attributes to be redefined if they were edited using the web
inspector. For example: <a-plane src="#groundTexture" rotation="-90.012 0 0" width="40" height="60" repeat="10 10" 
    position="39.548 0 -29.756" geometry="height = 20; width=10"></a-plane> this would cause the obj to have two
dimensions and then would not render within the mobile platforms. I was able to find this issue by going through
and commenting out everything and then slowly reintroducing them one by one until the problem was found and then 
corrected by only defining the dimensions only once.
                            


# Credits

Link sound: http://noproblo.dayjo.org/ZeldaSounds/

R2D2 sound: http://www.soundboard.com/sb/sound/301591

Pokeball sound: https://www.emp3e.com/download/puDn4cO4xOg/sound-effects-pok%C3%A9mon-anime-9-the-pop-pok%C3%A9ball-sound.html

Overwatch sound: https://overwatch.gamepedia.com/Category:L%C3%BAcio_sound_files

Futurama sound: http://www.futurama-madhouse.net/sounds/1acv01.shtml

Switch sound: https://www.myinstants.com/instant/nintendo-switch-click-69023/

Saucer sound: http://www.moviewavs.com/php/sounds/?id=bst&media=WAVS&type=TV_Shows&movie=X-Files&quote=xfiles.txt&file=xfiles.wav

Dinosaur sound: http://soundbible.com/1748-Tyrannosaurus-Rex-Roar.html

Squid sound: http://www.mariomayhem.com/downloads/sounds/new_super_mario_bros_wii_sound_effects.php

Fallout sound: https://www.dropbox.com/s/26kuqbckegj5hh9/Pipboy%20%26%20UI%20Sounds.rar?dl=0

Record Scratch sound: http://www.freesfx.co.uk/soundeffects/vinyl_record_players/

Vader sound: http://www.thesoundarchive.com/play-wav-files.asp?sound=starwars/swvader01.wav

Robot sound: http://soundbible.com/1170-Morse-Code.html

Teh LaughingMan: Planet Express Ship
https://poly.google.com/view/4FjZ6AzqTQI

Poly by Google: Flying Saucer
https://poly.google.com/view/fojR5i3h_nh

Alberto Calvo: Switch
https://poly.google.com/view/brxBpvrkAEA

Timothy 'YM' Johnson: Squid
https://poly.google.com/view/bUjvcUjUIfi

Hoai Nguyen: Tricerabot
https://poly.google.com/view/1FwnmJcupxI

Corentin Fatus: Poke Ball
https://poly.google.com/view/1AlBTqf2w22

Mason: Pip-Boy Model 3000 IV
https://poly.google.com/view/25Z6YXY6mSC

Tomas Bayer: Overwatch Lootbox
https://poly.google.com/view/euS1riZCDXo

Don Carson: Gramophone
https://poly.google.com/view/9MZ0sCt1REv

Alberto Calvo: Link
https://poly.google.com/view/a1vmc5a1IIG

Jarlan Perez: Toilet Paper Roll
https://poly.google.com/view/2oyXb4vEPaj

Lesley Klassen: Guest Chair
https://poly.google.com/view/e3LikHhpJsF

Danny Bittman: Couch | Wde
https://poly.google.com/view/7Q_Ab2HLll1

Jarlan Perez: Rug
https://poly.google.com/view/eYK3HHiuwRV

Colin McKibben: Flourescent Fixture
https://poly.google.com/view/b434Bd1ozKE

Danny Bittman: Standing Lamp
https://poly.google.com/view/aZyMp9TEk0I

Thomas Balouet: Mounted Lamp
https://poly.google.com/view/2KRNNF2ndWt

Maxwell Planck: Fantasy Tank
https://poly.google.com/view/4XjRDOSpazi

Vladmir Ilic: Vr-Mobil
https://poly.google.com/view/6XXj6DSBb08

Amy Hendricks: Robit
https://poly.google.com/view/b1YcejyrNtO

Poly by Google: Closet
https://poly.google.com/view/2qdm7DZVG94

Mikael Ganehag Brorsson: Server Rack:
https://poly.google.com/view/60s93Adyxvj

Like picture:
https://www.shareicon.net/approve-thumb-like-872775

Roommate of the Month Banner:
http://www.picturetopeople.org/p2p/text_effects_generator.p2p/3d_steel_text_effect

Hunter Paramore: Table
https://poly.google.com/view/7qAyGZnerYt

Poly by Google: Shelf
https://poly.google.com/view/fAfJzZmQpgY

Justin Randall: Bulb
https://poly.google.com/view/8Px7hO6zcfg

Don Carson: Camping Stuff
https://poly.google.com/view/3GSiSGRuyfT

Poly by Google: Computer Desk
https://poly.google.com/view/4U4lI91VbsO

Jonathan Granskog: Box Shelf
https://poly.google.com/view/3aAw-c_7gkO

Wesley Thompson: Garage Door
https://poly.google.com/view/4zdVu_Lk3sV

Mario Tofani: Wizard Table
https://poly.google.com/view/fpd7imG8Vxa

Don Carson: Little Bookcase
https://poly.google.com/view/74tXfxoDB9b

Ashley Alicea: Washer & Dryer
https://poly.google.com/view/fuQfwKQtq-7

Poly by Google: Bathroom
https://poly.google.com/view/3qqka8Oxe2B

RachelRunningWild: Bathroom Texture
http://rachelrunningwild.me/peachy-design-kitchen-wall-tiles-texture/sensational-kitchen-wall-tiles-texture-inspiring-25-for-room-decorating-ideas-with/

Justin Randall: Window 
https://poly.google.com/view/dwBpM-aSA_t

Lachlan Sleight: Cozy Kitchen 
https://poly.google.com/view/6bOTntCJyyK

Eric Finn: R2D2 
https://poly.google.com/view/dPgkqmBDqgH

Adrian Hon: Bedroom
https://poly.google.com/view/bbDbt2LwIfY

Remy Tauziac: Drill
https://poly.google.com/view/bhOpjMLGCVp

Poly by Google: Fireplace 
https://poly.google.com/view/6XDexoAkTD2

Poly by Google: Bed 
https://poly.google.com/view/9ycLAR71SmR

Wanja Pflüger: BookShelf 
https://poly.google.com/view/15B0ihXkg3C

SBarry: Sofa 
https://free3d.com/3d-model/sofa-27121.html

Hesen: Wall HDTV 
https://free3d.com/3d-model/hd-tv-28251.html

Adrian Hon: Bar v2 
https://poly.google.com/view/9f9xBGPIrtp

Sciman101: Door 
https://poly.google.com/view/eexB7rtcCTT

m.newlove: firework.wav
https://freesound.org/people/m.newlove/sounds/118932/

kjpargeter: Black quilted texture 
https://www.freepik.com/free-photo/black-quilted-texture_871291.htm#term=leather_sofa&page=1&position=0

TCP Library: Shelf texture
http://www.tcplibrary.org/2018/01/teen-january-programs.html

Garage Texture: 
http://texturelib.com/texture/?path=/Textures/concrete/floor/concrete_floor_0059

Star texture: 
https://www.artstation.com/artwork/1De53

Scott English: StarDestoryer.obj 

All rights reserved to the Disney Corporation: Star Wars
