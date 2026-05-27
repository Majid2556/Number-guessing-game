# Number-guessing-game

import random 
number = random.randint(1, 100)
while True: 
    guess = int(input("Guess: "))
    if guess == number: 
        print("You guessed correctly")             break 
    elif guess < number:
        print("Bigger") 
    else: 
        print("Smaller")
