# Hangman
import time
def W():
    time.sleep(2)
    print("Your guess is correct",  "first word is 'W'")
def I():
    time.sleep(2)
    print("Your guess is correct", "scnd word is 'I'")
def N():
    time.sleep(2)
    print("Your guess is correct", "third word is 'N'")
def T():
    time.sleep(2)
    print("Your guess is correct", "forth word is 'T'")
def E():
    time.sleep(2)
    print("Your guess is correct", "fifth word is 'E'")
def R():
    time.sleep(2)
    print("Your guess is correct", "sixth word is 'R'")

name = input("What is ur name: ")
time.sleep(2)
print("Hello " + name + ", hope you are sick :D")

secret_word = "FORTNITE"  # Word in caps as all input will be "Titled" that means all letter will be caps on
l1 = W
l2 = I
l3 = N
l4 = T
l5 = E
l6 = R
# l = letter. May be edited to add or discard according to the "secret_word"
print("*********************RULES*********************")
print("1. U only may enter every word once cuz if u enter a letter twice it may count as another try") #simple words: Programs not that good XD
print("2. Console should be all the way up")
time.sleep(2)
print("Loading game...")
print("Loading game..")
print("Loading game.")
time.sleep(1)

guess1 = input("Enter your guess for l1: ")
if guess1 == l1:
    W()
elif guess1 == l2:
    I()
elif guess1 == l3:
    N()
elif guess1 == l4:
    T()
elif guess1 == l5:
    E()
elif guess1 == l6:
    R()
else:
    print("Thnx for wasting my time")

guess2 = input("Enter your guess for l1: ")
if guess2 == l1:
    W()
elif guess2 == l2:
    I()
elif guess2 == l3:
    N()
elif guess2 == l4:
    T()
elif guess2 == l5:
    E()
elif guess2 == l6:
    R()
else:
    print("Thnx for wasting my time")

guess3 = input("Enter your guess for l1: ")
if guess3 == l1:
    W()
elif guess3 == l2:
    I()
elif guess3 == l3:
    N()
elif guess3 == l4:
    T()
elif guess3 == l5:
    E()
elif guess3 == l6:
    R()
else:
    print("Thnx for wasting my time")

guess4 = input("Enter your guess for l1: ")
if guess4 == l1:
    W()
elif guess4 == l2:
    I()
elif guess4 == l3:
    N()
elif guess4 == l4:
    T()
elif guess4 == l5:
    E()
elif guess4 == l6:
    R()
else:
    print("Thnx for wasting my time")

guess5 = input("Enter your guess for l1: ")
if guess5 == l1:
    W()
elif guess5 == l2:
    I()
elif guess5 == l3:
    N()
elif guess5 == l4:
    T()
elif guess5 == l5:
    E()
elif guess5 == l6:
    R()
else:
    print("Thnx for wasting my time")

guess6 = input("Enter your guess for l1: ")
if guess6 == l1:
    W()
elif guess6 == l2:
    I()
elif guess6 == l3:
    N()
elif guess6 == l4:
    T()
elif guess6 == l5:
    E()
elif guess6 == l6:
    R()
else:
    print("Thnx for wasting my time")
