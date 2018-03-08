---
title: Lesson 10-Making a conversation
layout: post
author: louis.webber
permalink: /lesson-10-making-a-conversation/
source-id: 1yn6-Xq3Y-8eAijqLrk2kNlwCUesdMpTrl2suzqZhBMY
published: true
---
Wednesday 7th March 2018

This lesson, we stopped working on our shape drawing on repl.it, and started to make some code to ask some basic questions like: "What is your name?", “Are you well today?” and “Do you like dogs or cats or neither?” At the end of the lesson, my code looked like this: 

print("Hello there!")

name=input("What is your name?")

print("Nice to meet you,", name +"!")

while True:

  print("Are you well today," ,name+"? Yes/No")

  feel=input()

  if feel.lower() == "yes":

    print("Glad to hear it!")

    break

  elif feel.lower() == "no":

    print("What a pity!")

    break

  else:

    print("Sorry, I don't understand that reply.")

