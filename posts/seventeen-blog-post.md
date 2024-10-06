---
title: Week 10 Session 1
published_at: 2024-09-30
snippet: 
disable_html_sanitization: true
allow_math: true
---

## Assignment 3 Playtesting and Feedback

Although my environment was not completed, I still thought it would be good to get some feedback at this stage on the effectiveness of it in various aspects from different players. In this first round of playtesting, these are the results I obtained.

![photo 1](photos/58.png)
![photo 1](photos/59.png)
![photo 1](photos/60.png)
![photo 1](photos/61.png)
![photo 1](photos/62.png)
![photo 1](photos/63.png)
*Results*

Additonally, I did spot some mistakes and technical errors during the playtesting, such as the lack of a collider for the tallest tower, so players got confused when they went through the wall while trying to climb the stairs. I also realised that some assets looked misaligned so I knew I had to rectify that as well.

While playing the games of my classmates, I was amazed at how technically proficient and creative they were. I learnt a lot and was inspired to improve my game.

## Gamification
The idea for players to find the 3 children that I hid in my scene was an idea that struck rather randomly the day before playtesting, so I gave the instructions to my playtesters verbally. I am glad that they seemed to enjoy the little 'game' I included in my environment, so I knew I had to develop a way to display this information within my scene.

My first idea was to try a UI pop-up that appears when the player spawns into the game. But after trying out a few methods shown in tutorials, I could not achieve what I wanted. Thus I decided to make it a physical game object instead.

![photo 1](photos/64.png)
*Top Left: First design, Top Right: Developed Design, Bottom: Game View*

I played around with the fonts and colours to find the correct contrast and good readibility. I think that this sign serves my intention well so I'm satisfied with it as an alternative!

## Audio

I learnt that assigning the audio source to the right game object was crucial. Because the main soundtrack overpowered all the other sound effects I added into the scene, I needed to change the audio source to one slightly further away from the other sources while still covering the same maximum distance, so that the sound effects can be heard clearer.

## Technical Issues 

I was very thankful for the video that was posted in the resource server on using occlussion culling to accelerate fps because my computer was starting to lag. Unfortunately thereafter, I did run into the issue of objects being clipped because of occlusion culling. However, I managed to resolve this by clearing and rebaking the occulsion of all objects, and turning off dynamic occlusion for the affected objects.

Another odd issue I faced was that a model that I made in Blender had faces that became invisible when imported into Unity, I found out that this issue had to be fixed in Blender, by flipping the normals of the faces of the object. So I managed to resolve that.

![photo 1](photos/65.png)
*Left: The original problem, Right: Solved*

## Creative Issues

After mostly populating the main area, I realised that the terrain looked very awkward. While I wanted the player to focus on getting to the main area, I could not overlook the background looking incomplete. I think this became a problem because I mostly referenced 3D animations for my environment, where everything is consciously presented in a constricted 2D frame. But since the game is in a 360 space, I needed to take care of the scene that is on the outside of my frame of focus.

Throughout the project I needed to do quite a lot of distancing, because I could be staring at my scene for period of time and had no inspiration and direction to move forward. By going for walks and constantly looking for other works to reference on Behance and Pinterest, the ideas eventually came to me. But I was definitely frustrated at myself sometimes because of this.

## General Reflections

This assignment and its accompanying modules was my introduction to Unity. As someone who doesn't play video games, I definitely felt out of my depth the past couple of weeks. In an attempt to make up for this, I spent a lot of time observing 3D forms on Pinterest, watching Unity and Blender tutorials and experimenting all sorts of things in Unity. I also felt a wave of accomplishment and relief as I watched people enjoying my game. I will definitely work on more 3D projects in the future!

# :cloud: A Place That Lives In My Memory

The title I have chosen for this project is <b>*A Place That Lives In My Memory*</b>. 

<blockquote>“The next best thing to the enjoyment of a good time is the recollection of it.” –James Lendall Basford</blockquote> 

My childhood that was spent with my siblings is a time I can never physically revisit again. But the memories forever live in my mind and soul, and this environment is a manifestation of the love and happiness of a time that I hope I will never forget. Even as the three of us continue to grow older and life inevitably changes us as people, I'm glad that I get to keep these memories and look back on them fondly.

## Credits

Audio Credits

Soundtrack:
Dream Escape By The Tides via Youtube Audio Library
Rainbow Forest by Quincas Moreira via Youtube Audio Library

Sound Effects:
Indoor Nice Fish Tank Ambiance by Pixabay
Rumbling Wind by Youtube Audio Library
Turnstil rx by Pixabay
Music Box by Pixabay
Open and Closed Door by Jurij via Pixabay
Iten Pick Up by Pixabay
piglvelwin2 by Pixabay
Arcade UI 16 by floraphonic via Pixabay

Model Credits

Messy Bed by thethieme
Chisley Club -RRES by Crane
TV by Shedmon
Lego Bricks by BlackCube
Sony Remote Tv by Admin Rezaei
Technics CD Player by ustoopia
Loshadka. Rocking horse wooden toy by timmoffey
Baby Chair by fabbear
Laila Dining Chair by mujbrah
Teddy bears by hectopod
Bedside Table by jspurlin
Beach Ball by Tommyleeney
Lego Plane by InterrMyl
Lego Plane by Luuk
MULA Maze (ikea toy)
Children Stool by JungleBird
Slinky Toy by Studio Lab
Green Crayon by Magnetron
Lego Man by McManus Media
Low-poly Jigsaw Puzzle Pieces by Gahar.Munir
Play-Doh clay compound by vaedskalw
Door with frame by witnessk
3 coloured dice by LukeModels75
Underwater Scene Version 2 by Vighnesh Baidu
3D Cartoon Balloons by Sufi_Artist
Uno Cards 3D by alia.wicaksans
Jenna Wooden Blocks Game
Gary (SpongeBob) by Yang Designs

Via SketchFab

[Here]() is the link to download the game.

## :rainbow: If you're curious...

I thought I could end off this blog post by explaining some of the more intricate details behind the project. 
