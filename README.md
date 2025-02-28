# Number-Guessing-Game-in-python ❇️

# cod Parts🐍

import random 
def number_guessing_game(): 
num = random.randint(1, 100) 
tries 7 
print("Guess a number between 1 and 100") 
while tries > 0: 
guess = int(input("Your guess: ")) 
if guess == num: 
print("You win!") 
return 
elif guess < num: 
print("Too low!") 
else: 
print("Too high!") 
tries -= 1 
print(f"Tries left: (tries]") 
print(f"Game over! The number was {num}.") 
number_guessing_game() 
