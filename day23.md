# A mental model of intelligent machines

Although it might be a streth for us to understand fully connected layers and deep neural networks at this point in the program, we can certainly think about how computer technology can
be used to enhance our project. At this point it is not necessary for us to understand at a detailed level how each and every machine learning algorithm works but instead we can 
work on building a mental model of what we think should happen and then we can explore some of the tooling options available to us to get a better understanding if what we would like to
make happen is possible or not.

Ideally we would like to explore artificial intelligence products that mimic human intelligence and help us infer certain information about our problem area. If we were working on the NBA analytics
problem we might need to explore the kinds of data being collected during each game and how we can use that data.

NBA games happen in real time and those games are then recorded via video and streamed on TV either in real time or via video recordinds. We have video data that we are working with in that case.
This data is a form of sequence data meaning each moment captured in the data is timestamped and the order of the data points matters. The fact that clip A occured before clip B is important because the action that
happened in clip B could increase or decrease the score board. We are specifically looking at shooter performance in this project so the scoreboars is important.

## Sh-sh-sh SHOOTER

What is in a shot? What does it mean to shoot? Uh- well, what does it mean to score in the game of basketball? We have a player who shoots the basketball towards the hoop and in order for
the shot to be a successful shot the ball needs to go into the hoop. If the ball does not go into and through the basketball hoop, the shot was unsuccessful. As we examine our video dataset
we need to keep track of who is taking a shot and if they made the shot or missed the shot. It is also important where the player attempted to score from on the court. Half court shots are much
more difficult than free throw shots and shooting while being heavily gauraded is more challenging then taking a wide open shot. All of this is important when thinking about what it means to be a good shooter in the game.
These figures should go into our shooter performance metric and we need to collect data examaning those scenarios for the players we are interested in examining their performance.

If we care about Steph Curry for example lets discuss the video data points we might need to collect:

- In one game all instances where steph curry took a shot, this would probably include a link to the video footage of the game and a start and stop timestamped list of every instance in that game he took a shot.
- from that list we can add location data to each point, we need to determine where on the court he was when he took the shot
- we need some sort of shot grid to geomap his location on the court when he took the shot
- we need some sort of shot difficulty score that takes into account distance from the basket, and the number of players who were gaurding him when he took the shot

### What is computer vision

So far we pointed out the data we are collecting was image data or video sequence data more specifically there are algorithms we can use to determine what is going in the frame of any image. The subdomain within 
artificial intelligence that thinks about what is happening in an image is known as computer vision. In any given image we now have algorithms that can detect objects in an image and this known
as image segmentation. We might care what the objects that we detected are like a person vs a cat. We have even gone so far as to recognize faces using facial recognition software that can classify a person
as say Stephen Curry vs another player. Yeah - computer vision is cool.

# what about the audio?

I am not too familiar with audio detection algorithms but I do know that we care about certain sounds in the game. The shot clock alarm is one sounds that is important and lets
us know when a player has run out of the time alloted to take a shot. We also care about the sounds of the movement of the net alterting us that the ball actually went though the net and a successful shot did
happen. Games are loud and so that particular sound might get drowned out by all of the other sounds that we hear during a game. Are there any algorithms that we can think of that could drown out noise
or possibly parse an audio file looking for a particular noise? What might this look like? How would we input this information into our algorithm, what would we expect the algorithm to output?

> possibly some booloan value that would indicate whether over a time period in the clip we found the sound we were looking for or not?
