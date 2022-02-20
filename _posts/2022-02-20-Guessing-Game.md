I have written my first program in the Automate the boring stuff lessons. It is a guess the number game. 

# This is a guess the number game.
import random

print('Hello. What is your name?')
name = input()

print('Well, ' + name + ', I am thinking of a number between 1 and 20.')
secretNumber = random.randint(1, 20)

for guessesTaken in range (1, 7):
    print('Take a guess.')
    guess = int(input())
    
    if guess < secretNumber:
        print('Your guess is too low.')
    elif guess > secretNumber:
        print('Your guess is too high.')
    else:
        break # This condition is for the correct guess!
    
if guess == secretNumber:
    print('Good job, ' + name + '! You guessed my number in ' + str(guessesTaken) + ' guesses.')
else:
    print('Nope, the number I was thinking of was ' + str(secretNumber))

This is section 5 of the Udemy course. A complete and working program, it is simple, with the concepts I have been learning that made it very straight forward. 

I am still excited about it. I am looking forward to learning more, and finally automating some boring tasks. 
