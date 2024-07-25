---
title: Unlocking New Adventure!
published_at: 2024-07-24
snippet: An example of a blog post.
disable_html_sanitization: true
allow_math: true
---


## The Explosive Cup of Coffee: A Scavenger Hunt Adventure
*Given the task of finding specific items around our new home, we embarked on an adventurous scavenger hunt. The first intriguing items on the list was an "explosive cup of coffee". We weren't sure what it meant, but we were determined to find out..*
![exploding coffee](coffee.jpeg)

## Digital Media Wisdom Book: to the Library!
*Our scavenger hunt continued. The next item on our list was a "book containing digital media wisdom". Intrigued by the prospect, we headed towards the library, a place we had yet to explore in our new home.*
![book of wisdom](book.jpeg)

## The Flying Paper Cargo: Both Intriguing and Perplexing
*Despite our best efforts, we couldn’t decipher its meaning or figure out where to find it. Determined not to get stuck, we decided to seek some expert advice. Still within the library, we hoped that the knowledgeable staff might be able to help us.*
![net trung above](net.jpeg)

## The Sith Lord's Study: A Familiar Place
*Determined to figure out why the room felt so familiar, I led my friends and retraced our steps through the library. We arrived at a part of the library I’d visited several days ago, during a different event.*
![study space](study.jpeg)

## The Faraway Beverage Machine: Seeking Guidence yet Again
*After our realization that the “wide machine dispensing beverages from a faraway land” was a vending machine, we needed to find one to continue our scavenger hunt. Remembering our previous success with the library’s helpful staff, we decided to ask Mrs. X , the librarian we had met before.*
![vending machine](machine.jpeg)



## This is h2

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


