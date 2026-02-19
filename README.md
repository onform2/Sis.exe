==========================================================
                         PROJECT: SISYPHUS.EXE
==================================================================

Author: Dreaming (DS14)
Module: CC0
Tooling: p5.js / JavaScript

         ,....,
      ,::::::<
     ,::/^\"``.
    ,::/, `   e`.
   ,::; |        '.
   ,::|  \___,-.  c/
   ;::|     \   '-'
   ;::|      \
   ;::|   _.=`\
   `;:|.=` _.=`\
     '|_.=`   __\
     `\_..==`` /
      .'.___.-'.
     /          \
    ('--......--')
    /'--......--'\
    `"--......--"

-----------------------------------
ARTIST STATEMENT
----------------------------------------------------

This project originated as an exploration of loops during the third week 
of my studies. I became captivated by the concept of "silent violence"—a 
zeitgeist of the modern era. We often think of violence as something 
bloody and ruthless, but there is a distinct, contemporary violence 
that is silent and slowly destructive. It is a violence enacted through 
systems, rituals, and the automated behaviours of our daily lives.

For me, there is a unique brutality to the "closed loop." Especially in 
the current era of technology, and considering the future of Artificial 
Intelligence and super-intelligence, these technologies signal the 
"walls closing in" around us. While there is a fear that this leads to 
"anti-truth," the far scarier threat is the minimization of human 
existence down to a raw set of quantifiable metrics. We are approaching 
a reality where things once considered mystic, spiritual, or intangible 
are reduced to measurable values, stripping away the illusions of 
freedom we once inhabited.

In developing this work, I was drawn to the story of Sisyphus through 
the lens of Wolfgang Ernst and his concept of micro-temporality (2013). 
Ernst describes a state where time exists strictly at the level of the 
machine, fundamentally divorced from the human experience of duration. 
Sisyphus’s existence—an impossible, repetitive task—mirrors this 
machine logic. It adds a bittersweet melancholy to the idea of 
immortality and brings a "syncopated brutality" to the concept of 
infinity.

In questioning whether this repetition is one of suffering or 
satisfaction, I looked to Albert Camus (1942), who famously concluded 
that "one must imagine Sisyphus happy" because the struggle itself is 
enough to fill a man's heart. However, when looking deeper into Gilles 
Deleuze’s distinction between mechanical versus complex repetition 
(1968), I became focused on the "closed loop" as a denial of autonomy. 

As Deleuze suggests, we often believe we have ultimate freedom, yet we 
are simply "executing instructions with perfect fidelity" within the 
parameters of physics, society, and "machine" logic. This artwork 
attempts to summarize these thin tracks from which we cannot be moved.

Originally, I envisioned a 3D render akin to a video game title screen: 
a warrior running toward the camera, perpetually stopped and corrupted 
by a glitch just as he reaches his goal. However, achieving the 
necessary aesthetic polish in 3D using p5.js proved "janky" and 
unrealistic. I am a firm believer that to break the rules, 
one must first master them; I wanted to avoid a "juvenile" or 
unpolished look.

I pivoted to a 2D aesthetic, leveraging my experience in pixel art to 
create custom sprites. While the art was more labour-intensive than 
anticipated, I limited the sprite-heavy events to three specific 
triggers, ensuring the rest of the glitch events were handled purely 
through code to maintain a "software art" aesthetic rather than just a 
pre-rendered animation.

/*
              .
             / \
            |   |
            |. .|
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
            | : |
       _.._ | : | _.._
     /     `\ :/`     \
    |  |=|   | |   |=|  |
    |  |=|   | |   |=|  |
     \_____. | | ._____/
        _   `| |`   _
       (_/   | |   \_)
            [###]
            [###]
            [###]
            [###]
            [###]
            [###]
            [###]
           (####)
          (######) 
*/

Technical execution required a rigorous debugging process involving over 
100 iterations of "save-state" files. To manage the technical 
complexity, I developed a Beta testing environment that allowed me to 
trigger 20+ glitch events via a button-based interface. This, combined 
with rigorous console.log debugging, allowed me to refine the State 
Machine Management. 

The most complex task was the State Machine Management: keeping track 
of whether the Knight was running, jumping, or striking, while 
simultaneously managing the currentGlitch variables and the 
glitchProgress timer. This required significant organizational thinking. 
Each fix provided the knowledge required to implement the next, more 
complex effect—from simple RGB shifts to the "Floor Collapse" and 
"Pixel Burst."

The result is a piece of non-interactive software art that speaks to 
the fragile state of human struggle against the alien existence of 
machine logic.

------------------------------------------
5. REFERENCE LIST
----------------------------------------------------------

Camus, A. (1942). The Myth of Sisyphus. London: Penguin Books.

Deleuze, G. (1968). Difference and Repetition. Translated by P. Patton 
     (1994). New York: Columbia University Press.

Ernst, W. (2013). Chronomediation: The Temporal Dimension of Media. 
     Cambridge: MIT Press.

Schiffman, D. (2012). The Nature of Code: Simulating Natural Systems 
     with Processing. [Self-published]. Available at: 
     https://natureofcode.com.

The Coding Train. (2016). 11.3: The Pixel Array - p5.js Tutorial. 
     [Online Video]. Available at: 
     https://www.youtube.com/watch?v=nMUMZ5YRxHI.

Workman, K. (n.d.). Happy Coding: Pixel Manipulation Tutorials. 
     [Online]. Available at: https://happycoding.io.

========================================================
                           [END OF FILE]
======================================================================
