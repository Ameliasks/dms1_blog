---
title: Week 8 Session 1
published_at: 2024-09-16
snippet: 
disable_html_sanitization: true
allow_math: true
---

# :page_with_curl: Classroom Task - Experiments

![photo 1](photos/40.png)
![photo 1](photos/41.png)
*Experiment with HDRIs and optical illusion*

For my optical illusion/ anamorphic experiement, I utilised the terrain scene from the last lesson and juxtaposed it with a moon. I wanted to make the moon appear to be very large, but in fact, it is just positioned very close to the camera. 

I wanted to familiar myself with using SkyBox and HDRIs as I know I would need this knowledge on lighting later on in my own project. I also found new grass texture maps, just to see if the lighting effect works on materials with texture.

![photo 1](photos/42.png)
*Importing SketchFab models and adding colliders*

Ran into a few technical difficulties during this activity, such as not applying the mesh collider correctly and the character ontroller not working due to the step offset being more than 0, which I must have accidenly tweaked when going through the camera settings. As well as the silly mistake of not deleting old cameras.


# :page_with_curl: Week 8 Session 1 Homework - Assignment 3 Progress

![photo 1](photos/48.png)
*Adding paths to greybox*

After creating the most basic forms of my project, I realised I needed to add paths to help the user navigate each podium 1 by 1. To achieve this, I used ProBuilder to create ramps. For the regular slope, I adjusted the vertices to combine it into the podium, and for the curved ramps, I used a bezier shape to curve the ramp around the podium, then adjusted the vertices. I used more curved/spiral paths for the second area as I envisioned it to look somewhat like a theme park.With this mix of straight, oblique and spiral paths, I hope that the player will be excited to explore the environment I designed.

![photo 1](photos/50.png)
*New greybox model of environment*

## Technical Hiccups

![photo 1](photos/50.png)
*Problem*

While using Unity, I encountered the weirdest error of an object I deleted from the hierachy, still showing in my scene. It was unclickable and could not be moved. To solve this, I onto forums, where I found a script called *Hidden Object Explorer*. Using this script, I managed to find and delete the object from the back end.

