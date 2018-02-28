---
title: Lesson 9-Repl.it
layout: post
author: louis.webber
permalink: /lesson-9-repl.it/
source-id: 1bEX_dROHZJ75mhK5VBdg4R3Po3CdYP5H12fepFyv2qA
published: true
---
Wednesday 28th February 2018

This lesson we swapped groups, so now instead of doing work on Google Sheets, we worked on a website called 'Repl.it'. In this website we used simple commands such as:

for number in range(4):

turtle.forward(120) 

turtle.right(90)

So what this means is it will draw a line 120 pixels long, then turn 90 degrees clockwise and draw another line the same length. It would repeat this 4 times, therefore making a square. By the end of the lesson though, aare code looked more like this:

import turtle

turtle.speed(100)

turtle.shape("turtle")

def draw_shape(sides,length):

  for number in range(sides):

    turtle.forward(length)

    turtle.right(360/sides)

    

So what this does, it draws all the shapes with side number 3 all the way through to 8, like this: 

