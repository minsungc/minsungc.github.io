+++
title = "The bots make me feel dumb and the worst part is I know exactly why"
date = "2026-06-16"
description = "."
tags = [
]
+++

It's because they code for me.

My code usually spends just as much time in my head as it does being written down on the computer.
I find that thinking deeply about what I plan to write makes my mistakes stand out.
An edge case that I need to cover, an optimization I didn't do, an abstraction I couldn't
come up with -- all things I catch at "firing neurons to type my thougLet's hts" time.
And these mistakes help me be a better programmer.

Indeed, one of the things that I learned early in my computer touching is that
_I am in complete control over my own code_.
The computer is simply following your instructions, so your instructions need to reflect
your thought process.
And this reflection is a skill I can control and hone.

When I started experimenting with my company's Claude Code (🤖) subscription, I still had complete control.
The 🤖 simply carried out the instructions that my hands were too lazy to write.
"Grep for this". "Write a test case for this edge case". "Translate this code into Go".
Not surprisingly, it was very good at the rote tasks, especially when I did all of the thinking for it.

But slowly the control started to slip from me. That's not right, actually. More accurately I started
*giving away* my control. I let 🤖 devise plans and whirr away without me. I let 🤖 review its
own code and then summarize it in a cutesy little markdown file. (For some reason I did not let it commit
or push, as if I was hanging on to what little control I had.)

In giving away control I started unlearning how I program.
Code started taking less space in my brain, instead replaced by long, trailing sentences with em dashes and semicolons.
Data was going from point A to point B but I wasn't sure how.
By letting 🤖 become my hands, I accidentally also let it become my brain.

Things really came to a head when I realized I did not understand the code that 🤖 wrote anymore.
The code does what I want it to do, sure.
The tests pass and they check for what I want it to check.
But 🤖 writes code in a way so unintuitive, so black-box, that I spent more effort
trying to understand the slop than I would have spent writing things myself. I lost all control to 🤖.

I felt really dumb after realizing that. Luckily feeling dumb is amazing incentive, and it didn't take me long to
rein in my reliance on 🤖. It still codes faster than me -- I would imagine it does not take learning from the
entire internet to do so, but it also has that -- so I would say it's still a productivity boost.
But I am significantly more careful about what code it touches, and demand a quality standard from it that
I don't even ask for in PR reviews.

Anyway, moral of the story is that, in the end, I am a programmer. And programming is not simply writing
funny text and then pressing a couple buttons and having the computer magically spit out one gorillion dollars.
Programming is about communicating what you want to a computer, and understanding that ultimately it
is your responsibility to communicate precisely and accurately. Then maybe, just maybe, I might stop feeling dumb.