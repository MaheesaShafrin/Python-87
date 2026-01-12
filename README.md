# Python-87
 Python program to draw a circle of squares using Turtle
import turtle

x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle + 10)  # slight rotation for spiral effect

for i in range(36):
    square(90)

turtle.done()
