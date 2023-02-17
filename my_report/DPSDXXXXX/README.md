
# Lesson: Digital & Serious Games

### First and Last Name: Paraskevi Evelina Kallergi
### University Registration Number: dpsd18139
### GitHub Personal Profile: https://github.com/dpsd18139
### Digital & Serious Games Personal Repository: https://dpsd18139.github.io/Role-Playing-Game/

# Introduction


Hello, 
you're currently reading the introduction I wrote for my ongoing assigment for my GameDev university class.
As you're reading this, you're about to embark on a jounery with me.
One filled with blood, sweat and tears, but also passion.

Enjoy:)

![Sprite-0001](https://user-images.githubusercontent.com/115796369/212590839-9c774dd0-a559-406a-8980-bebbd0d03744.png)

✿✿✿

# Summary

Here I'll summarize the vision I originally had  for this game.

I wanted to make a game that appears to be self aware of it's existence as a university project.
To make such a game you have to break the 4th wall of immersion multiple times.

Whether I accomplished my original goal is up for debate,
but ultimately this is a game that has been evolved consciously alongside it's progression in the development phase. 
It's packed with meta humour, mostly concerning it's incompleteness.

Below I offer a log of my original thoughts during each development phase, based on the deliverables.

I thought about editing it to fix the typos, but decided not to in order to preserve the rawness of emotions I had during the process.
I recommend that you play the game since you might be left a bit confused just by reading this. 

:)

✿✿✿

# 1st Deliverable

I wrote a story draft about this game's plot. 
Then I made some concept art of my two characters. The main character, who is controlled by the player was designed in a way to appear androgynous/gender ambiguous. This way both genders will be able to put themselves in the characters shoes, without men having their fragile masculinity threatened. The other character is a mysterious young girl, at first glace appearing devoid of human emotion and common video game logic. As the game progresses we will learn more and more about this game through this character.


![IMG_1281](https://user-images.githubusercontent.com/115796369/208269375-c52488ca-0d13-48cf-8268-aa89fd233a0e.PNG)

![IMG_1521](https://user-images.githubusercontent.com/115796369/208269405-640b520e-bdf5-4e12-b996-bc833957677d.PNG)

![IMG_1283](https://user-images.githubusercontent.com/115796369/208270565-f5b275f1-669a-4081-acfb-85ca8be7df7f.PNG)


Then I used this character generator to create our character sprite models in a way that would correspond to the concept art I made earlier.
My initial plan was to make my own 2D pixel art sprites and animation, but I couldn't do it in time for this deliverable. I intend to do so for the next one.
https://picrew.me/image_maker/36838

![MC2 0_test1](https://user-images.githubusercontent.com/115796369/208270570-cb4410b8-72cb-42a6-ada9-6e6eee5eb7b3.png)

![Dee](https://user-images.githubusercontent.com/115796369/208269467-e0911848-187d-4de6-9a61-c3ef6b081dfc.png)


After that I used a tile map I found on itch.io to create this map. My original goal was to find one that looks like a small night city but couldn't find find one that matched my vision so I used this one as a placeholder for the deliverable.

The graveyard is a crucial part of the story, so I intend to keep it.

I added a simple coloured semi transparent rectangle sprite as a filter to simulate a soft evening feel.

Lastly, I used a nostalgia inducing piano song I found on YouTube as backround music. Again, I originally intended to create my own music for this project, but again, I indend to do it for the next one!

https://www.youtube.com/watch?v=YOxZh2OaydM

I also intend to fix  the colliders.

P.S. I hope you're able to find the small easter egg i added :)

((spoilers :) ))

![Στιγμιότυπο οθόνης 2022-12-18 015020](https://user-images.githubusercontent.com/115796369/208270491-ac826669-0b66-4b7d-aa95-5936ec16ecff.png)

✿✿✿

# 2nd Deliverable
I spent 2 days in front of my laptop and added so many things I don't remember the exact order, but I will do my best to make my fried brain remember.

First I decided to edit my main character's sprite so that they can change direction when the player presses a key.

I designed and drew the new pixel art sides myself using the pixel art program editor aseprite.

![IMG_1322](https://user-images.githubusercontent.com/115796369/208270582-d3882ba0-6604-427d-8f72-8a6c16e74dd5.jpg)

Here is the after.

![IMG_1324](https://user-images.githubusercontent.com/115796369/208269650-3bbb7cab-ffb9-4ef3-9729-e8de98fb8d31.GIF)


Then I imported them into the game to test the animator. It worked but simply changing the direction of my character while walking did not feel natural enough.

Sooooooooooooo

I decided to animate four directions of walking myself ( for the first time) .

![IMG_1523](https://user-images.githubusercontent.com/115796369/208270594-cd087aed-823b-4344-9b58-d64211e0b9ea.jpg)

I  drew the walk using 8 frames for each direction.

Again this is the four gifs I drew.

![MC2 0_front](https://user-images.githubusercontent.com/115796369/208269669-dcb02047-b0de-450f-8b7f-bab21caf8b31.gif)
![MC2 0_left](https://user-images.githubusercontent.com/115796369/208269671-f0a0e37e-fd0e-4c12-9dfc-1f6748acfe68.gif)
![MC2 0_right](https://user-images.githubusercontent.com/115796369/208269673-0dfe6019-18fe-46df-b2a5-cab2f2a2d63b.gif)
![MC2 0_back](https://user-images.githubusercontent.com/115796369/208269674-c708af01-f996-47b3-b4ed-9c132d1cd342.gif)


I imported everything in unity and fixed the animation so that the player can switch between a state of moving (using the walking animation), not moving 
(while holding the previous direction of the character).

Then the deadline almsost came up and I had 2 days to complete everything else.

So I got serious.

First I added a scenemachine camera to my game, it made the feeling a bit smoother.

I had already added collisions on the previous assignments, and I didn't intend to fix it on this scene, because I still plan on changing the map.

But I adjusted the pivot point on my sprites and it made everything seem a bit more immersive.

I added health to my player. 

Then I Added Enemies. First I added an animated spike trap.

![RlYTwO](https://user-images.githubusercontent.com/115796369/208269872-55477228-285a-4ab5-8a76-aa14b780cc4c.gif)

Then an animated Red slime. I programmed them to move in a square and do damage to my player. 

![4TsZ10](https://user-images.githubusercontent.com/115796369/208269857-f34f20fc-aa88-4ea7-bdd8-46dc59810f74.gif)

Then after testing I found out that 5 lives are far too many and I wanted the game to be a bit less forgiving. So I reduced the max health to 3 health points 
and set the invincibility timer from 2 to 0.5.

After all that I discovered that there will be no way to tell the changes made to the player's health in the current state of the deliverable. 

So I opened up aseprite editor and added a red transparent layer on top of the 4 sides of the character to use them as custom animations, indicating when they player
gets hit. I imported them to unity and the game could show when the player gets hit.

![fronthit](https://user-images.githubusercontent.com/115796369/208270719-06d7f8d2-b55a-4999-9350-b9d01ab91912.gif)

However there was no indication for when the health gets to zero. So I programmed a game manager added a custom script to reset the scene after the player gets hit.

After that I also decided I want to have the players currenth health visible to the player so I also added a text mesh pro object and a script to change it.
I also imported a custom pixel font for a more universal look. 

![tRRefY](https://user-images.githubusercontent.com/115796369/208269839-757279f3-c5ab-4340-b7b7-84cc7903b033.gif)

![Στιγμιότυπο οθόνης 2022-12-18 013805](https://user-images.githubusercontent.com/115796369/208270050-a3bcf370-15cc-49ef-81a3-f2741923bef4.png)


I downloaded some food sprites I found online and added a jar of marmelade to heal the player because I love marmelade. I added projectiles so I used the steak sprite from the same pack. No specific reason why I chose steaks.

![Στιγμιότυπο οθόνης 2022-12-18 013845](https://user-images.githubusercontent.com/115796369/208270441-c1b322dd-bfef-439d-8b16-059343d813e2.png)


![Food](https://user-images.githubusercontent.com/115796369/208270067-905aa611-7258-4c3b-a5de-13232d54b87f.png)


In the end, I wanted to make the npc character get angry and chase down the player if they hit her with the projectile 3 times, but I couldn't find a way in time 
for the deliverable so I chose not to. And I made her unfreeze her rotating on the z axis whet being hit inspead.

Here is the chasing script though, it works and I plan on adding it next time.

![IMG_1519](https://user-images.githubusercontent.com/115796369/208269732-67d29663-b9df-41b6-bec4-f2c78fb87e32.jpg)

But I wanted the game to feel a bit more interactive so I left behind messages for the player if they get near the icon of the old compurter disk on the left.

I made it work with isTrigger 2d box colliders and made the text change once they exit it there will be a second message, but there's a bug and the player might miss the first message if they throw a projectile on the area or dont stay long enough to read it, I intend to fix on the next version.

Here are the two texts I added in case you missed them, but I recommend playing the game first because they kinda spoil it.

![Στιγμιότυπο οθόνης 2022-12-18 013943](https://user-images.githubusercontent.com/115796369/208270012-6948402d-dbfe-4d0c-8835-95d65e9852ba.png)

![Στιγμιότυπο οθόνης 2022-12-18 014028](https://user-images.githubusercontent.com/115796369/208270018-06be83df-93e6-45e9-87c3-00114eb65257.png)

I also did some post processing to make the game more atmospheric, hopefully inducing the feeling of a dream.

You know the drill, Before 

![IMG_1510](https://user-images.githubusercontent.com/115796369/208269757-9f500c01-199d-4d92-ac01-e90f27208098.jpg)

And After 

![IMG_1512](https://user-images.githubusercontent.com/115796369/208269762-1fadb26b-8a57-478f-a5c4-2c03dad66c23.jpg)


Finally I wrote another small story ( only one chapter for now) so that I can get inspired to make this game something that is worth playing on it's own.
My hope is that this game will live on even after the end of the semester and we will be left with a nice story to experience.

You can find the draft on the my_report>dpsd18139 folder.
But here is the link for convenience.
https://github.com/dpsd18139/Role-Playing-Game/blob/main/my_report/dpsd18139/BehindTransientGarden_ch0.pdf

✿✿✿

# 3rd Deliverable 
Seeing my pale reflection in the mirror, I realise I haven't been outside in 3 days. Again, I spent so much time on this I am bound to have forgotted some things.

First, I decided what is missing most from my game, is a menu. Don't ask me why. I just like variety, I guess.
So after I spent half a day on finding a way to animate overlay opacities via script, I made a mini animation like menu for my main screen.

![menu](https://user-images.githubusercontent.com/115796369/212586035-ba62f8a1-45b1-4594-94dc-dbc1431f3443.png)
![menuoprions](https://user-images.githubusercontent.com/115796369/212586299-ece444c1-2454-4afc-9d4d-0f8088049e51.png)


The optipns are: 
* Play: Loads the first scene
* Options: Enables Option menu, where I added a functional audio slider, that saves the player's preference throughtout the game.
* Extra: this is an extra button. It's so extra it doesn't even have a function.

![soundcode](https://user-images.githubusercontent.com/115796369/212586349-6e6b4e04-e1ce-44ee-a213-6f3af3ad634c.png)


Also I founda way to use my post processing settings on UI elements too :)

After all these, I decided I wanted to stay true to the original vision of the story, so I made the inside of the house of the Main Character.
After that I added the necessary collisions and a note from the NPC to the player.

But I needed a way for the character to exit the house and be teleported to the main scene.
For this, I put a trigger collider on the door, because I liked the feel of instantly being transported rather than having to press a button in order for
a ray cast to work.

Do not worry though, I am using raycast for something else later down the line *dialogue cough cough*

![house](https://user-images.githubusercontent.com/115796369/212586480-35576fd0-441a-414b-9254-1a0c6c48b54c.png)


((I also added a temporary way to be transported inside, I might turn it into  a house exterior later. ))

After that I thought I'd try my hand at particles.
I wanted to simulate leaves falling down from the sky in the main scene.
So I used a sprite sheet from this asset pack called Ninjas Adventure on Itchio!
[Uploading YzEJnE.gif…]()

ALSO I ADDED RAYCAST!!!!!!!!!!!!!!!!!!!!!!!!1!

[Uploading ddddddddddddddd.png…]()

When the player enters the trigger collider of my NPC, a message pops out and tells them to press E to talk to her !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

![ddddddd](https://user-images.githubusercontent.com/115796369/212587743-ffdf4c80-8663-4510-b28c-806886b1748e.png)

I also fixed the script for my NPC to chase the player. But she won't collide with any object because she's a ghost!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
![m3](https://user-images.githubusercontent.com/115796369/212589011-17cb3fde-273b-4a0c-a715-bcb0520814bf.png)

Finally, I added more messages for the player in different records. I named them DevNotes.
There are 9 in total and I was planning to make a score counter for them but I thought I would do something more original.

If you're too bored to find them, I suppose I could show some of them here. But not all.
![m1](https://user-images.githubusercontent.com/115796369/212588480-e11909bc-8a12-425b-ba65-9ef6a3d87631.png)
![m2](https://user-images.githubusercontent.com/115796369/212588495-d7271add-00b9-49bc-9431-a62beb162b83.png)

I added a BIG Message (and a sound) If the player collects the final record, and another one when they die (no sound just silence). 

![uded](https://user-images.githubusercontent.com/115796369/212589315-17f8f64d-2b90-44e0-a2cb-e90f120a0722.png)

AND LASTLY I also added a sound for the projectiles, as well as a script that emits particles if the projectile hits and object.

✿✿✿

# Conclusions
My back hurts, I need a better chair and I'm way better at developing a game than I was at the start of the semester.

This was harder than I anticipaated, but not impossible. 

✿✿✿

# Sources

* Tilemap: https://cainos.itch.io/pixel-art-top-down-basic
* Character Generator:https://picrew.me/image_maker/36838
* Music:https://www.youtube.com/watch?v=YOxZh2OaydM
* Animated Traps: https://stealthix.itch.io/animated-traps
* Slime Enemy: https://warsvault.itch.io/high-fantasy-slime-enemy 
* Food Icons: https://henrysoftware.itch.io/pixel-food
* RPG Icon demo: https://franuka.itc
* h.io/rpg-icon-pack-demo
* Silver font: https://poppyworks.itch.io/silver
* Ninja Adventure: https://pixel-boy.itch.io/ninja-adventure-asset-pack

✿✿✿

# Tools
Aseprite: https://dacap.itch.io/aseprite

======
