# turtle-art-
input_email == turtle.art()

def new_function():
    import turtle
    turtle.bgcolor("black")
    turtle.pensize(1)
    turtle.speed(0)

    for i in range(150):
        for colours in ("blue","green"):
            turtle.color(colours)
            turtle.circle(100)
            turtle.left(10)

turtle.hideturtle()


while True:
    try:

        name = input(" Enter your email here: ").lower()
        password = int(input(" Enter your password here: "))

        if name == "shikisenri123":
            if password == 123456789:
                new_function()
                print(" input credentials was correct!")

        else:
            print("wrong credentials, please try again...")
    except ValueError:
        print("input of zero is excluded, please try again...")



