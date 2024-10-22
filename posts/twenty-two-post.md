---
title: Week 12 Session 2
published_at: 2024-10-18
snippet: 
disable_html_sanitization: true
allow_math: true
---

# :page_with_curl: Assignment 4 Progress

I knew that I wanted to insert some stroke vector graphics as a visual element to amplify each part of the artist biography, and decided to go for a pixel art look for these graphics as I thought they would complement the font and colours I was using. I knew from using Figma previously that there is a community page where designers and engineers can upload resources that are free to use, and I managed to find [this](https://www.figma.com/community/file/1196864707579677521) Figma file that provided free pixel icons. I liked this set of icons because they included the icons I had in mind, like the pencil, lightbulb and video, and they also had just the right amount of deatil.

I also went through the design to make sure there were no text widows. (In typesetting, widows and orphans are single lines of text from a paragraph that dangle at either the beginning or end of a block of text.) 

![photo 1](photos/91.png)
*Left: Original, Right: Edited to remove widow* 


## Animation Workflow

Using [this](https://youtu.be/pIF_zIDaZ94?si=bO1yMGRKNl2lWRLr) tutorial, I learnt how to do 'scroll' animations in Figma prototype. Due to Figma not supporting actual scroll animations, how this imitation effect is achieved is through making each section an indivdual component, then through making variants of these components, adding a mouse over interaction and applying the smart animation effect. I did face a fair share of issues when i first started the animations, and was very worried I could not complete all the animations I had in mind on time. Thankfully, I managed to troubleshoot these issues and becae more meticulous in executing the steps so that the animation would work smoothly. I did all the animations on a duplicate of the original frame, so that I still could constantly reference the design and layout while creating the animations in a separate frame. Being able to compare them side by side was also extremely useful for spotting inaccuracies.

![photo 1](photos/87.png)
*Final Frame with Components*

## Creating Mobile Layout

I copied the original design without animations into a separate page in the same file. The reason for this was because at the time, I needed to prioritise creating the mobile layout over completing the animations. In addition, duplicating over the animations could make it much harder to adapt the design to a mobile layout. Using [this](https://youtu.be/gwiX0oASlEw?si=-4t915w5MgOHOIW0) tutorial on responsive layout in Figma, I started to make modifications to the layers so as to create an efficient adaptation workflow. This included framing and grouping layers, and using auto layout.

To start, I knew that the font sizes had to be modified, as the current size would have been too huge for a small phone screen. I also modified the margin and gutter of the column guide to one better suited for mobile layout. I did rough research on the ideals specs for these parameters.

![photo 1](photos/88.png)
*Ideal Margin Size*
![photo 1](photos/89.png)
*Ideal Font Body Size*

Once I decided on the new font sizes, I made new text styles so that I would be able to efficiently change all the text sizes if need be.

For the mobile layout, I chose to work with the specs of iphone16 pro.

When the scale of the photos were reduced to fit the new aspect ratio, the rounded rectangles that I had in my design had to be adjusted as well, as the strokes became too thick and and the angle too rounded. But this was easily rectified.

## Finishing Touches

After completing the animations and mobile layout, I started to think about what other details were required for the site, and how to further develop the webcore style I was aiming for. One such detail was adding the links to the videos for 'Leaving The Nest' and 'A Place That Lives In My Memory' and the deno site for 'What's In A Home'. I needed to find a way to include these links because Figma in its free version, does not support video embedding or external site embedding.

So I thought about how to display the links, I decided to utilise the pixel game look and create a button component that would sit on top of the hero images of each project and animate it in sequence with each image. However, since Figma also does not support embedding links onto objects, I had to create an invisible text layer with the site link attached to it, so as to fake the button being able to direct to the link on click.

![photo 1](photos/92.png)
*Button Component Implemented*

My landing page is surprisingly, what I completed last. I think I was slightly intimidated to complete it, since it is most probably the most important part of the whole site, with the duty to capture attention and leave a strong first impression. I worked with the placeholder thus far, as I was not sure what images I wanted to use for the web windows. However, I knew I wanted the images to look intriguing and colourful.

In the end, I decided to manipulate images of the 3 projects featured on the site, save for the centre image which I used it as it was. The left image is a still render captured from the Unity project, but I applied a mosaic smart filter on it on Photoshop, to make it look extremely pixelised. For the bottom image, I took one of the icon illustrations and removed the background, imported it into Figma and duplicated it to create an abstract, glitch effect. And finally for the top most image, I screenshotted from the first assignment the shot of the school, and in Photoshop, used a liquify smart effect, hue and saturation layer and curves layer to create a trippy look.

![photo 1](photos/93.png)
*Inspirations for the landing page* 

I had many ideas from these inspirations, but I realised after trying to pile on layers, that going too complex and maximalist would not really complement the rest of the site. So I settled for something a little more simplistic with just enough detail in the end.

To further exaggerate the 8-bit, pixelised game look of the site, I added small boxes randomly across the about page and at the section transitions in between each project description. I thought that this would help provide a little more visual interest to the site, and not make the colour sections look as stiff.


## General Reflection

I have had experience making profolio sites, having just made my second one earlier this year before I enrolled into this course. As such, I took this assignment as an opportunity to further push myself and challenge a style I have not really explored, but still quintessentially me.





