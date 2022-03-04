# QuestionGame
It's basic question game
# I'm going to create an English question game

import turtle
wn = turtle.Screen()
wn.title("Simple English Question Game By Gogo-bean")
wn.bgcolor("white")

# import tree pic and move to left
wn.register_shape("Tree1.gif")
game_eng = turtle.Turtle()
game_eng.shape("Tree1.gif")
game_eng.goto(-450, -100)
game_eng.speed()

# second pics
wn.register_shape("sun.gif")
game_eng = turtle.Turtle()
game_eng.shape("sun.gif")
game_eng.goto(400, 220)
game_eng.speed()

# third pics
wn.register_shape("bird1.gif")
game_eng = turtle.Turtle()
game_eng.shape("bird1.gif")
game_eng.goto(450, -50)
game_eng.speed()

# fourth pics
wn.register_shape("cloud.gif")
game_eng = turtle.Turtle()
game_eng.shape("cloud.gif")
game_eng.goto(-10, 95)
game_eng.speed()

# fifth pics
wn.register_shape("box.gif")
game_eng = turtle.Turtle()
game_eng.shape("box.gif")
game_eng.goto(80, -60)
# import "Hello Everyone"
game = 0
pen = turtle.Turtle()
pen.hideturtle()
# pen.color("black")
pen.penup()
pen.goto(-10, 80)
pen.write(f"Hello Everyone! ", align="center", font=("Arial", 32, "normal"))
# Question
pen.penup()
pen.goto(80, -70)
pen.write(f"Do you want to play game? ", align="center", font=("Arial", 28, "normal"))

wn.mainloop()
