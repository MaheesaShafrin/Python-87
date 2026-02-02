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

Output:

<img width="409" height="413" alt="Screenshot 2025-12-19 133631" src="https://github.com/user-attachments/assets/dccb1361-9f50-4361-91bc-21a9ff9203b2" />
