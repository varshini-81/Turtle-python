# Turtle-python
Simple designs square by turtle

import turtle
def fn(n):
    t.penup()
    t.goto(-n,n)
    t.pendown()
    for _ in range(4):
        t.fd(2*n)
        t.rt(90)
t=turtle.Turtle()
fn(200)
fn(100)
turtle.done() 
