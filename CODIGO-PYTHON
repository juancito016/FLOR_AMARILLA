from turtle import *
import turtle as tur

tur.bgcolor("darkgrey")

tur.penup()
tur.left(90)
tur.fd(200)
tur.pendown()
tur.right(90)

tur.fillcolor("yellow")
tur.begin_fill()
tur.circle(10, 180)
tur.circle(25, 110)
tur.left(50)
tur.circle(60, 45)
tur.circle(20, 170)
tur.right(24)
tur.fd(30)
tur.left(10)
tur.circle(30, 110)
tur.fd(20)
tur.left(40)
tur.circle(90, 70)
tur.circle(30, 150)
tur.right(30)
tur.fd(15)
tur.circle(80, 90)
tur.left(15)
tur.fd(45)
tur.right(165)
tur.fd(20)
tur.left(155)
tur.circle(150, 80)
tur.left(50)
tur.circle(150, 90)
tur.end_fill()

tur.left(150)
tur.circle(-90, 70)
tur.left(20)
tur.circle(75, 105)
tur.setheading(60)
tur.circle(80, 98)
tur.circle(-90, 40)

tur.left(180)
tur.circle(90, 40)
tur.circle(-80, 98)
tur.setheading(-83)

tur.fd(30)
tur.left(90)
tur.fd(25)
tur.left(45)
tur.fillcolor("dark green")
tur.begin_fill()
tur.circle(-80, 90)
tur.right(90)
tur.circle(-80, 90)
tur.end_fill()
tur.right(135)
tur.fd(60)
tur.left(180)
tur.fd(85)
tur.left(90)
tur.fd(80)

tur.right(90)
tur.right(45)
tur.fillcolor("green")
tur.begin_fill()
tur.circle(80, 90)
tur.left(90)
tur.circle(80, 90)
tur.end_fill()
tur.left(135)
tur.fd(60)
tur.left(180)
tur.fd(60)
tur.right(90)
tur.circle(200, 60)


# Agregar texto
tur.penup()
tur.goto(0,310)  # Posición donde deseas agregar el texto
tur.pendown()
tur.color("black")  # Color del texto
tur.write("PARA TI HERMOSA!!", align="center", font=("Stencil", 45, "italic"))


# Mueve la pluma a la posición donde deseas dibujar el corazón
tur.penup()
tur.goto(330, 310)  # Cambia las coordenadas según tus preferencias
tur.pendown()

# Configura el relleno del corazón
tur.fillcolor("red")
tur.begin_fill()
tur.pensize(1)

# Dibuja la mitad izquierda del corazón
tur.left(140)
tur.forward(40)
for _ in range(200):
    tur.right(1)
    tur.forward(0.3)

# Dibuja la mitad derecha del corazón
tur.left(120)
for _ in range(200):
    tur.right(1)
    tur.forward(0.3)

# Completa el corazón
tur.forward(40)

# Finaliza el relleno del corazón
tur.end_fill()

# Cierra la ventana al hacer clic en ella
tur.exitonclick()
