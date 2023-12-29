def kekanan():
    turn_left()
    turn_left()
    turn_left()

def pindah():
    move()
    kekanan()

pindah()
move()

while not at_goal():
    if front_is_clear():
        move()
        if right_is_clear():
            kekanan()
            build_wall()
            turn_left()
    else: 
        turn_left()
