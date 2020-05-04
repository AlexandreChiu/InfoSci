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
```python

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
```
    
5//4/2020
 What are some ways in which Computer Science can help the fight against Covid-19?
In your opinion, should people enable access to the resources of their personal computers as tools for research? Are there any risks?

Computer Science can fight against Covid-19 is by trying to understand protein folding by running computer simulations of how the proteins work and operate.
Yes, I think people should enable access to the resources of their personal computers as tools for research as it probably doesn't take too much of your device’s computational power and it uses your computer when it is idle or not active. It might seem like it doesn’t help with hundreds of thousands and millions of computers. It can save researchers a lot of time and effort. The risks are: computer safety and privacy, and your computer being slowed down due to the use of your computational power. However, these issues are tackled because the program uses extensive security safeguards to ensure the system is protected from hacking and difficult to exploit .It really makes a difference in the long run and can help finding cures for viruses a lot easier and faster, benefitting not only the researchers but everyone in the world. 

Code for Task 3

```python

# definition of variables
posx = 300;
posy = 300;

def setup():
    size (500,500)
def draw():
    global posx, posy
    background(255)
    strokeWeight(2)
    
    #create individual
    posx = posx + random(-10, 10)
    posy = posy + random(-10, 10)
    circle (posx, posy, 40)

    
    #boundaries conditions
    if posx > 500:
        posx = 500;
    if posy > 500:
        posy = 500;
    if posy < -500:
        posy = 500;
    if posx < -500:
        posx = 500;
        
delay(100)
```

Task 4

```pyton

#definition of variables
x = []
y = []

def setup():
    size(500,500)
    for i in range(10):
        x.append(random(0,500))
        y.append(random(0,500))
        
def draw():
    background(255)
    strokeWeight(2)
    global x,y
    
    #First individual
    for i in range(10):
        circle(x[i],y[i],40)
        x[i] = x[i] + random(-10,10)
        y[1] = y[i] + random(-10,10)
        
        if x[i] > 500:
            x[i] = 500
        if x[i] < 0:
            x[i] = 0
        if y[i] > 500:
            y[i] = 500
        if y[i] < 0:
            y[i] = 0

    delay(100)
   
    
```


   



Task 5
What should be some behaviours (at least 3) that we will need to include in our simulation to be a realistic approximation of the current situation in the world? Explain.

1. We need a way to represent the differnet types of people who are ill such as people who are criticcally ill, people who have mild symptoms, people who are asymptomatic

2. We need a way to represent countries and each individuals nationality.

3. We need to include a way to represent countries from least developed to most developed, that way we can know which countries are the most able and have the most advanced resources to help cure the ill

