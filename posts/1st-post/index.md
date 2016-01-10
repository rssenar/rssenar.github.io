<!-- 
.. title: 1st Post
.. slug: 1st-post
.. date: 2016-01-07 18:06:18 UTC-08:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->


## Links

This is an [example inline link](http://lmgtfy.com/) and [another one with a title](http://lmgtfy.com/ "Hello, world").

Links can also be reference based : [reference 1][ref1] or [reference 2 with title][ref2].

References are usually placed at the bottom of the document

## Images

A sample image :

![B-Wing](https://dl.dropboxusercontent.com/u/4423832/Websites%20Images/b_wing_redesign_by_stephen_daymond.png)
![B-Wing2](https://dl.dropboxusercontent.com/u/4423832/Websites%20Images/Bwing_negvv.jpg)
![B-Wing3](https://dl.dropboxusercontent.com/u/4423832/Websites%20Images/rock_splitter_9_by_shimmering_sword-d8akb3t.jpg)
![B-Wing4](https://dl.dropboxusercontent.com/u/4423832/Websites%20Images/Star-Wars-Rebels-Season-Two-23.jpg)

## Code

It's quite easy to show code in markdown files.

Backticks can be used to `highlight` some words.

Also, any indented block is considered a code block.  If `enable_highlight` is `true`, syntax highlighting will be included (for the builtin parser - the github parser does this automatically).

    <script>
        document.location = 'http://lmgtfy.com/?q=markdown+cheat+sheet';
    </script>

## Math

When `enable_mathjax` is `true`, inline math can be included \\(\frac{\pi}{2}\\) $\pi$

Alternatively, math can be written on its own line:

$$F(\omega) = \frac{1}{\sqrt{2\pi}} \int_{-\infty}^{\infty} f(t) \, e^{ - i \omega t}dt$$

\\[\int_0^1 f(t) \mathrm{d}t\\]

\\[\sum_j \gamma_j^2/d_j\\]