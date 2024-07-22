---
title: Digital Media Studio 1 
published_at: 2024-07-22
snippet: Studio 1 Scavenger Hunt
disable_html_sanitization: true
allow_math: true
---

# Studio 1 Scavenger Hunt :detective:
My Scavenging Team™️ consists of 5 members: Jacqueline, Jill, Lachy, Ruby, and myself. 

## 1 - An explosive cup of coffee.
![An explosive cup of coffee.](blob:https://web.telegram.org/48913d53-9cf0-451c-9445-943756ef7550)
## 2 - A book containing Digital Media wisdom, found amongst many.
## 3 - A wide net strung above, bulging under the weight of its flying paper cargo.
## 4 - A curtain of roots, delivered by a winged visitor.
## 5 - A door for the condemned.
## 6 - A study space fit for a Sith Lord.
## 7 - The disembodied hands of a great ape.
## 9 - A wide machine, dispensing beverages from a far away land.
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


