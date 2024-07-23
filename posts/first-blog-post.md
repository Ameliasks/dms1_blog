---
title: Digital Media Studio 1 
published_at: 2024-07-22
snippet: 
disable_html_sanitization: true
allow_math: true
---

# :detective: Studio 1 Scavenger Hunt 
My Scavenging Team™️ consists of 5 members: Jacqueline, Jill, Lachy, Ruby, and me. 

## 1 - An explosive cup of coffee.

![photo 1](photos/1.jpg)
*Pictured from left to right: Ruby, Lachy, Jacqueline, Jill and me in front of Bowen St. Cafe*

After we made our quick introductions, we hurried out with the other teams, eager to begin the hunt. We decided to start working on the checklist from the first item : 'An explosive cup of coffee.' Although we could not quite decrypt what 'explosive' meant, I suggested going to the closest cafe to our starting point, Bowen St. Cafe. Agreeing to make do with this location as the temporary answer to possibly revisit later, we took our first selfie here.

## 2 - A book containing Digital Media wisdom, found amongst many.

![photo 2](photos/2.jpg)
*Us at the Swanston Library with 'The Poetics of Digital Media*

Perhaps the most time-consuming of all our attempts, this item led the team to the Swanston Library. Completely new to and unfamiliar with the library, we were slightly overwhelmed with where to start. Jacqueline and Jill made the astute decision to search through the library directory for books with titles including 'digital media'. We realised then that we were on the wrong floor and and went downstairs to continue the search. Althought it took us a considerable amount of time to scour through the shelves, we eventually found one of the books we saw on the directory (with a little help from the librarian), as pictured above, called 'The Poetics of Digital Media'.

## 3 - A wide net strung above, bulging under the weight of its flying paper cargo.
*Us at the Swanston Library with the net of paper cranes*

While exploring the library for the previous item, Ruby and I passed the net of paper cranes by chance and brought the rest of the team in for the photo. 

![photo 1](photos/3.jpg)

## 4 - A curtain of roots, delivered by a winged visitor.
*Us on Bowen Street with the installation*

When I saw the word 'roots' I immediately thought of the buildings 2,4 and 6 on Bowen Street, but could not draw the association between any of them and a 'winged visitor*. Upon seeing the installation at the front of building 8, Lachy mentioned that the way the roots covered the open staircase behind it makes it appear as a curtain of sorts. 


![photo 1](photos/4.jpg)

## 5 - A door for the condemned.

![photo 1](photos/5.jpg)

## 6 - A study space fit for a Sith Lord.

![photo 1](photos/6.jpg)

## 7 - The disembodied hands of a great ape.

![photo 1](photos/7.jpg)
## 9 - A wide machine, dispensing beverages from a far away land.

![photo 1](photos/9.jpg)

## The Unsolved - #8 and #10

Completely clueless and out of time, we unfortunately returned to the studio without deciphering 2 of the clues: a basement-dwelling Black Box, bigger than you might think and a golden globe atop a tower of eights. Despite that, I enjoyed the opportunity this activity gave me to get to know some of my classmates on my first day of university.


![a drippy lemon](logo.svg)

^ images are written like this: `![description](file_path/static/logo.svg)`

*This is italic.*[^1]

[^1]: This is a footnote, *which can also be italic*.

**This is bold.**

Hyperlinks can be written like this: `[text](https://URL)`

You can find a markdown cheat-sheet [here](https://www.markdownguide.org/cheat-sheet/).

## Maths:

... which can be written inline, like this: $\{ x, y, z \} \in \N$

... or block, like this:

$$ x^2 + y^2 = z^2 $$

Visit [ $\KaTeX$ ](https://katex.org/docs/supported#fractions-and-binomials) for more information about writing maths.

## Embedding video:

<iframe id="coding_train_video" src="https://www.youtube.com/embed/rI_y2GAlQFM?si=RDgjkpunxk1mQzMI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<script type="module">

    console.log (`hello world! 🚀`)

    const iframe  = document.getElementById (`coding_train_video`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16

</script>

## Embedding p5 sketches:

<iframe id="falling_falling" src="https://editor.p5js.org/capogreco/full/Fkg05m7aA"></iframe>

<script type="module">

    const iframe  = document.getElementById (`falling_falling`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 + 42

</script>

## Canvas API

<canvas id="canvas_example"></canvas>

<script type="module">
    const cnv = document.getElementById (`canvas_example`)
    cnv.width = cnv.parentNode.scrollWidth
    cnv.height = cnv.width * 9 / 16

    const ctx = cnv.getContext (`2d`)
    const pos = {
        x: -100,
        y: cnv.height / 2 - 50
    }
    
    function draw_frame () {
        ctx.fillStyle = `turquoise`
        ctx.fillRect (0, 0, cnv.width, cnv.height)

        ctx.fillStyle = `hotpink`
        ctx.fillRect (pos.x, pos.y, 100, 100)

        pos.x += 2

        if (pos.x > cnv.width) {
            pos.x = -100
        }

        requestAnimationFrame (draw_frame)
    }

    draw_frame ()
</script>


