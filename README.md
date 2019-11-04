# Some-Kind-Of-Game
### Goals

-   Creating a basic game starting with no knowledge of programming

### Boundaries / Scope

-   download a program that will allow me to create the game
-   

### Success criteria

-  the main controls work correctly
-  games properties function as they should

### Constraints

-   My lack of knowledge and lack of game creating program to start with

### Assumptions

-   the game will be represnted easily after its programmed
-   there will be guides on how to preogram and create this game
-   I can find created assets to use for my game

### Stakeholders

-   Professor - for grade
-   Parents - investing in my education and future success, want to make them proud
-   Perspective Employers - artifact will be added to my student portfolio which could help with getting a job

### Timeline

Week:

-   1.Find and download a game making program. (I am going to use unity) 3 hours deciding and downloading 2D Unity from the list of         options provided on the course website.
-   2.Toy around and figure out the programming (I'm looking at the example game and its files for a bit of a understanding) I               practiced with the sample 2D game for about 4 hours looking at the files, sprites, and tutorial videos.
-   3.Figure out the modeling or assets (I was able to download some free assets from the asset store) I spent about 2 hours looking         for the assets store and finding the assets I wanted to use. I also looked up videos of people using the same assets to see how         the character moves.
-   4.Start using some of the assets for characters and backgrounds (I was able to create the background and a platform with proper         layering.) I spent about 2 hours total looking for a tutorial videos on how to impliment tiles as the floor and placing a               background in the farthest back layering at -10 to not over layer the tile or potential sprites.
-   5.Figure out a common sprite animation for collactables (I created a coin using the animation tools and the images provided) It         took about 2 hours total to find and implement a tutorial about giving the coin proper animations, collision, and gravity to fall       on the floor. I also gave the tile collision in a way that it looks like the objects are in the middle of the grass.
-   6.Figure out how to use the character sprites and animations (I tried to use the images of the character as if it was a sprite           like the coin but it just shifted images instead of coming together.) I tried to find videos and tutorials about properly               implementing the PNGs given to me but I cound't find any easily and I accidently created a pulsateing peice of meat that was             only shifting though the images when i used the same method as the coin i created.
-   7.Put that character together (I finally found a tutorial talking about using each image seperatly and placing the character             together, I created the hero named "Meat", I even gave him a original idle animation using the animation tools. I attached a             picture of my Unity tool and the little area I made. I also uploaded a screen recording of the animations in action. I feel very         satisfied seeing the little hero animated and the coin colliding with the floor.) It took about 4 hours total to find a video, (it       took a while), about createing my hero with the seperate PNGs and creating the custom animations by using the Animation timeline         window and draging the body parts to create the aniamtions.
 -  8.I am looking around for various tutorials about giving my character movment but it turns out my little character is horrible and       does not function correctly at all. I decided to use a single picture for now to keep it simple until I understand how to create a       sprite sheet of my own and implement it properly. As I was searching I found a tutorial teaching a way to create a tile sheet, I         used this method instead of the long pieced tile I had created. It looks nicer and I can create platforms much easier now. I then       created a small area to test potential collision, gravity, and movment. I found some tutorials on youtube and tried following along     but I got compiler errors after about a hour of following along and I couldn't find what was wrong. These programs had me using C#       on Microsoft Visual Studio 2017 and I am trying my best to give the gravity and physics to a small chest as a test subject.
 -  9.I am still using various tutorials in hopes to properly code my sprite but they are complicated and using foreign symbols to me.       While I was on campus attending classes I found on google a tutorial from Unity themselves from their live sessions. When I got home     I followed along with the Recorded Video Session of 2D Platformer Character Controller. This tutorial looks good and the guide does     eveything step by step and explains what each piece does. I followed along and when I got to step 2 where we use code to script         gravity I followed along and when I tested it the chest.png the chest fell just like the example. Steps 3 and 4 is where the             complications started to occur, both steps need to be done before you can test the games characters and models but when I finished       step 4 I was getting the compiler errors again. I wasn't sure what was wrong so I went back in the video and checked every piece of     code to make sure I typed averything correctly and capatalized everything properly. After I checked the video for another hour I         tried again and the same error showed up, I then decided to look at the plain code they provide under the video and check my code       their. I had a few peices different from what was shown and I corrected my code but I still got the error, I got frustrated and         saved my original code in a different file and just copied and pasted the code from the example to the script. Of course this           didn't work either and now I am stuck with a large piece of code with a small error thats preventing me from continuing. (I am           providing my original code in Github so I don't loose it aswell)
 -  10.I decided to shift focus from the characters movment to creating a better beginning level that had higher floors and more detail,     I wanted to create hills that you can see the shape but the collisions are only on the top. I'm doing that to make it a                 platformer leading to the top of the (current) largest hill. I started by creating the top of the platforms and spaceing them out in     a way that jumping would work well without crashing the players head. After that I followed the edges of the platforms and created       the slopes to show they are hills and not dirt pillars. The lowest hills got layering priority and once all the edges were created I     simply filled the inside of the hills with a bucket tool. The one weird thing was that the slopes did not show the dirt of the           hills behind them, I tried to just put another tile but it would just show over the previous slope. I experimented with the layering     like I did with the background and created another grid and tilemap with less layering priority to fill the backround of the hills,     I am satisfied with the way the hills look but know I want to add some Envioromental Decor. I created another tilesheet using the       Enviroment png provided in the free assets. I then created another grid and tile map with much smaller cell sizes to be more             accurate with the trees, grass, bushes, rocks, and flower positioning. I placed them around carfully to make the spacing look good       and not to over use them. With a good area created I gave each platform a 2D box collider and I placed a copy of the coin I             previously created. With the level created I at least wanted to create some movment for now so I placed a circle collider on Luigi       and a edge collider under him at a angle so he rolls on the ground with no fiction at all until he collides with the coin. I looked     over the code for character movment again but I still get a compiler error so I will look at it again in the future and I plan on       trying to reach out to some professors that may have experience with unity.
