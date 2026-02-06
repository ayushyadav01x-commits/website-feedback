import random

score = 0
print("🏏 Hand Cricket Game 🏏")
print("Choose a number from 1 to 6")

while True:
    player = int(input("Your number (1-6): "))
    computer = random.randint(1, 6)

    print("Computer chose:", computer)

    if player == computer:
        print("OUT ❌")
        print("Final Score:", score)
        break
    else:
        score = score + player
        print("Runs scored:", player)
        print("Total Score:", score).
