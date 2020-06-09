# This is a number guessing game.
import random

guesses_taken = 0

print('Hello! What is your name?')
myName = input()

number = random.randint(1, 50)
print('Well, ' + myName + ', I am thinking of a number between 1 and 50.')

print(' Make a guess. \n You hane got five chances. \n Good Luck!!') 
while guesses_taken < 5:
    guess = input()
    guess = int(guess)
    guesses_taken = guesses_taken + 1
    if guess < number:
        print('Your guess is too low.')
        print('Try Again') 

    
    if guess > number:
        print('Your guess is too high.')
        print('Try Again')
    
    if guess == number:
        break

if guess == number:
    guesses_taken = str(guesses_taken)
    print('Good job, ' + myName + '! You guessed my number in ' + guesses_taken + ' guesses!')

if guess != number:
    number = str(number)
    print('Nope. The number I was thinking of was ' + number)
