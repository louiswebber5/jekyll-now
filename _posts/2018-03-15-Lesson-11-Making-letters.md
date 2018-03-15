---
title: Lesson 11-Making letters
layout: post
author: louis.webber
permalink: /lesson-11-making-letters/
source-id: 1_6oC4tMir0vk7R4qFGmrfUwpLFPcwD6LddPyEhQuTgI
published: true
---
Wednesday 14th March 2018

This lesson, we made letters on repl.it. The main functions we used were turtle.forward, turtle.backward, turtle.right and turtle.left. These are all pretty self-explanatory, the turtle would move a certain number of pixels forward or backward, or the turtle would turn a certain number of degrees left or right. The other functions we used were turtle.penup and turtle.pendown, which were also useful because you could 'lift' the pen up, move it to wherever you wanted, and carry on  drawing. This is what my code looked like at the end of the lesson:

import turtle

painter = turtle.Turtle()

painter.pencolor("green")

def draw_A():  

  turtle.left(75)

  turtle.forward(100)

  turtle.right(150)

  turtle.forward(100)

  turtle.backward(40)

  turtle.right(105)

  turtle.forward(30)

def draw_L():

  turtle.backward(100)

  turtle.right(90)

  turtle.forward(50) 

def draw_W():

  turtle.backward(98)

  turtle.right(30)

  turtle.forward(75)

  turtle.right(120)

  turtle.forward(75)

  turtle.right(210)

  turtle.forward(98)

draw_A()

turtle.penup()

turtle.left(75)

turtle.forward(40)

turtle.left(105)

turtle.forward(80)

turtle.left(90)

turtle.forward(98)

turtle.pendown()

draw_L()

turtle.penup()

turtle.forward(25)

turtle.left(90)

turtle.forward(98)

turtle.pendown()

draw_W()

