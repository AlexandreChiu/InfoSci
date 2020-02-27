What did we do?
We tried to make a jelly sandwisch by writing a set of instructions (algorithm) and learned how to create a repository
What did we learn?
We learned that algorithims are hard to write and create 
What questions do I have?
How are we going to start to learn programming, what's the first step in learning


6/2/2020
What did we do?
We created variations to the circles we created using code , such as adding lines to the circles, changing the color, size, and rate in which the cirlces appear. In the end, we tried to make a dice using our knowledge on how to create circles and squares. 
What did we learn?
We learned how to write simple code and created a bunch of circles using this new knowledge. We learned how to add color, how to randomize factors and variables
What questions do I have?
I want to know how to create and work with other shapes, as well as how to draw with these shapes. 

10/2/20
What did we do?
We finished completing our dice and added code that added range and with that range we could start doing problability. We added different problabilities for each side of the dice
What did we learn? 
We learned how to add range and problability. We also learned to randomize the sides so each time the side changes
What questions do I have?
What is the limit for the range and what other uses could problability have in coding

20/2/20
What did we do?
We created a chess board, wrote down the steps and instruction for creating it. Made the chess board into an optical illusion, and looked at other illusions online
What did we learn?
We learned how to create a chess board, by creating lines, adding squares and adding code to create a pattern of squares with spaces in between
What questions do I have?
Do these optical illusions have any uses in the real world. Can you also create a working chess board in Python?

27/2/20
What did we do?
We created our own illusions in python inspired by real life illsuions, presented our illusions and discussed on ways we could improve upon
What did we learn?
How to make illusions in code and how to present them
What questions do I have?
What uses do these illusions have in the real world other than confuse people.
```.py


def setup():
    size(400, 00)
    background(255)
    
def mouseClicked():
    global x, vertical
    x = (0, 700)
    vertical = (0, 700)
    
    shape = int(0)
    print(shape)
    if shape == 0:
        circle(5,5,5)
        circle(6,6,6)
        circle(7,7,7)
        circle(8,8,8)
        circle(9,9,9)
        circle(10,10,10)
        circle(15,15,15)
        circle(20,20,20)
        circle(25, 25, 25)
        circle(30, 30, 30)
        circle(35, 35, 35)
        circle (40,40,40)
        circle(45,45,45)
        circle(50,50,50)
        circle(55,55,55)
        circle(60,60,60)
        circle(65,65,65)
        circle(70,70,70)
        circle(75,75,75)
        circle(80,80,80)
        circle(85,85,85)
        circle(90,90,90)
        circle(95,95,95)
        circle(100,100,100)
        circle(105,105,105)
        circle(110,110,110)
        circle(115,115,115)
        circle(120,120,120)
        circle(125,125,125)
        circle(130,130,130)
        circle(135,135,135)
        circle(140,140,140)
        circle(145,145,145)
        circle(150,150,150)
        circle(155,155,155)
        circle(160,160,160)
        circle(165,165,165)
        circle(170,170,170)
        circle(175,175,175)
        circle(180,180,180)
        circle(185,185,185)
        circle(190,190,190)
        circle(195,195,195)
        circle(200,200,200)
        
def draw():
    delay(100)
