---
layout: post
title:  "Workshop 1 Draft"
date:   2021-04-06 00:00 +1000
author: "Vera Su"
tags: workshop, curriculum
---

### Last updated: April 14 2021

Please excuse the improper citation format.

***

# Introduction

Welcome to the first Music Computing Workshop! Today, we will focus on familiarising you with the BBC Microbit and some of its features. Don't be intimidated by this, it's just like sheet music but instead of the sheet music telling you what to do, you are using  sheet music to tell the Microbit what to do.

Feel free to discuss your thoughts with your peers at any point, or even speak up if you have questions! This is your chance to try out the Microbit and see if it can help you create cool music.

# Task 1 - Different Parts of the Microbit

Take a look at this photo of the Microbit. There are several different pieces. 2 buttons, an accelerometer, microphone, speaker and an LED screen. There's also the slots for battery, a USB port and a reset button. Look at the labeled images below and try and find each of these features.



# Task 2 - Hello World!

Let's get started with coding straight away! The first step of any programmer's journey is displaying Hello World on the screen, but let's switch it up a bit!

On your screen, you should have two *instructions*, play middle C for 1 beat and play middle D for one B. When your program reaches these instructions, it will *execute* them (aka do as it says). We also have a block called "on start". This means whenever the Microbit starts, it will do whatever you've put inside it.

So let's start by dragging the two instructions into the "on start" block. You can see if it works by clicking the start button and asking MakeCode to "play your code".

Time to experiment a little bit: Try to make the Microbit sing middle C and middle D three times!

# Task 3 - Functions?

If you're thinking, "hmm, that doesn't seem very efficient" then you're right! We essentially have a sequence of middle C and middle D, so why not combine it into just one instruction and reduce the lines of code by half?

On your screen, you should now an empty "function" block. When the program *calls* a function, the function will execute the instructions in that block. To *call* a function, we also need to give it a name. Let's call it beepBoop for now.

Now, you can make it sing middle C and middle D by dragging those instructions into the block, and then calling beepBoop in the "on start" block. Finally, you can call beepBoop (try to find this block yourself) three times to get the same effect as in Task 2, but with less code!

# Task 4 - Conditionals

Let's take a quick detour to talk about conditional statements. Don't be afraid of them! They're basically written flow charts.

Is it 5 o'clock? If yes then it's time to go home, otherwise I'm still in class.

Is it cold outside? If yes then I will wear my jacket.

x = 5? If yes then I will do this, otherwise I will do something else.

Now let's look at MakeCode again, you should see an empty If block a variable called number storing the number 5. In programming, a variable is basically a box that stores anything (a number, a sentence, a letter etc.)

All you have to do is fill in the blanks

Can you figure out how to make the Microbit sing beepBoop only when number is equal to 5?
Hint: Look under the comparison section of Logic.

Now to spice it up a little more, you can click the little plus button to create another empty block which will tell the computer what to do when number does not equal 5 (the otherwise part of a flow chart). Can you make it so that it sings boopBeep instead? You will need to make a new function for this as well.


# Task 5 - Repeats?

Looking back at our original code, we're still repeating call beepBoop three times. Surely there's another way to shorten this?

Introducing loops! MakeCode has an easy repeating block. Try using that to call beepBoop three times instead.

Next let's look deeper into the repeat block. How does it work? Well you start with a variable, which counts up for us. Each time we repeat, we also increase our counter by 1 until we reach the number of times we want to repeat (in this case 3).

Interesting note here, most programming starts counting at 0, not at one (this includes make code). So if we want to play something a total of 3 times, we should be counting from 0 to 2, not 0 to 3!

Can you figure out how to call beepBoop 3 times using the for block instead?

# Task 6 - Putting it all together

Amazing work today! To finish it all off I have a challenge for you. Pick a segment of any song that you like and try to make the Microbit sing! If you notice your code is being repeated, you can try using functions or loops to simplify.

If you're stuck for a song, try: The Swan by Saint-Saens.

*** 

## Random notes and thoughts

- Should I convert each task to be livecoding -> the students try?
- Add an extra task to explain lists and repeats part 2?

## References
1. [10 Quick Tips for teaching programming](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006023)
2. [COMP2300 Intro Lab](https://cs.anu.edu.au/courses/comp2300/labs/01-intro/)
3. [Functions first](https://www.researchgate.net/publication/305221737_The_teaching_of_functions_as_the_first_step_to_learn_imperative_programming)
