---
layout: post
title:  "Workshop 2 Draft"
date:   2021-04-19 08:00 +1000
author: "Vera Su"
tags: workshop, curriculum
---

### Last updated: April 19 2021

# Task 4 - Variables

That was a little bit painful to do and really time consuming... We essentially have a sequence of middle C and middle D, so why not combine it into just one instruction and reduce the lines of code by half?

On your screen, you should now an empty "function" block. When the program *calls* a function, the function will execute the instructions in that block. To *call* a function, we also need to give it a name. Let's call it beepBoop for now.

Now, you can make it sing middle C and middle D by dragging those instructions into the block, and then calling beepBoop in the "on start" block. Finally, you can call beepBoop (try to find this block yourself) three times to get the same effect as in Task 2, but with less code!

# Task 5 - Conditionals

Let's take a quick detour to talk about conditional statements. Don't be afraid of them! They're basically written flow charts.

Is it 5 o'clock? If yes then it's time to go home, otherwise I'm still in class.

Is it cold outside? If yes then I will wear my jacket.

x = 5? If yes then I will do this, otherwise I will do something else.

Now let's look at MakeCode again, you should see an empty If block and a variable called number storing the number 5. In programming, a variable is basically a box that stores anything (a number, a sentence, a letter etc.)

All you have to do is fill in the blanks

Can you figure out how to make the Microbit sing beepBoop only when number is equal to 5?
Hint: Look under the comparison section of Logic.

Now to spice it up a little more, you can click the little plus button to create another empty block which will tell the computer what to do when number does not equal 5 (the otherwise part of a flow chart). Can you make it so that it sings boopBeep instead? You will need to make a new function for this as well.

# Task 6 - Repeats?

Looking back at our original code, we're still repeating call beepBoop three times. Surely there's another way to shorten this?

Introducing loops! MakeCode has an easy repeating block. Try using that to call beepBoop three times instead.

Next let's look deeper into the repeat block. How does it work? Well you start with a variable, which counts up for us. Each time we repeat, we also increase our counter by 1 until we reach the number of times we want to repeat (in this case 3).

Interesting note here, most programming starts counting at 0, not at one (this includes make code). So if we want to play something a total of 3 times, we should be counting from 0 to 2, not 0 to 3!

Can you figure out how to call beepBoop 3 times using the for block instead?

# Task 7 - Putting it all together

Amazing work today! To finish it all off I have a challenge for you. I have given you a bit of sheet music. Can you translate it into code so that the Microbit can sing it?