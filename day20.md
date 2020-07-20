# Introduction to computer vision

I wanted to figure out the fastest way to introduce you to AI and although there are some really cool videos that you could review, there is also Fast.ai.

I would highly encourage you to review lesson 1, and definitely take notes. It might not make sense all at once immediately, but over time it will, but I want to to get a general idea of what is going on.

Explore the Fast.Ai site [10 minutes doing this]
Watch lesson 1 - image classification 
Load the notebook in co-lab and run all the cells, it doesn't matter if you don't know what is happening just run the cells.

Notebooks:
- [00_notebook_tutorial.ipynb]()
- [lesson1-pets.ipynb]()

Join the [forum]() and ask 1 question. Even if you aren't sure and you feel unprepared.
Watch the [first NLP lecture]() and read the course overview

## What is the big idea?
Lets say you have a bunch of images of animals and you want a computer to be able to classify the images. When we say classify images we mean group them or cluster them, the images without a label.
In order for a computer to do this the computer needs to to "learn" some general understanding of what an animal is lets think specifically about dogs and cats. We as humana able to interact with computers
generally understand the differences between dogs and cats. Dogs are typically larger and have different shaped traits like faces and paws. A computer can learn these differences as well by looking through
labeled examples of dogs and cats. If we create an image classification "model" or learning algorithm to classify images this model can start to understand the differences between dogs and cats by looking at say 50
images label cat and 50 images labaled dog. We can then show the model that we have just trained on a new unlabeled image and ask it to guess what kind of animal it is and apply a new label either
a dog label or a cat label. The computer will then use the "learning" that it did with the labeled images to make a guess about what label most accurately fits the new image either a dog 
or a cat.

This is a very high level explanation of computer vision, but it is general enough that we understand how this might be valuable. In our NBA analytics project we might want to identify when a player is 
taking a shot. When a player is taking a shot we want to record this and analyze whether the player makes the shot or misses the host and we can do this with computer vision.
It is up to use to "model" the computer vision problem because we don't yet have fully generalizable models that can tell us everything about an image at one point in time, but our modeling techniques are gettings
better and we can segment images and understand a LOT about what is happening in an image. There are a lot of corporate research groups working on problems in this domains and they 
use these techniques in their products. I think that creating a few posts about company spotlights might be useful in this respect.
