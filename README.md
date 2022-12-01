# hhh
from turtle import*
speed(30)
for i in range(3):
    for i in range(5):
        begin_fill()
        color("brown")
        for i in range(4):
            forward(10)
            right(90)
        end_fill()
        penup()
        forward(14)
        pendown()
    penup()
    back(70)
    left(90)
    forward(14)
    right(90)
    pendown()


penup()
forward(-(14 * ((11 - 5) / 2)))
pendown()

for i in range(6):
    for d in range(1):
        s = 11
        for g in range(s):
            begin_fill()
            color("green")
            for h in range(4):
                forward(10)
                right(90)
            end_fill()
            penup()
            forward(14)
            pendown()
            penup()
            g -= 2
        backward(14 * (s - 1))
        left(90)
        forward(14)
        right(90)
        pendown()
        
    

