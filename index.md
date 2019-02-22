## Welcome to Carel's Page

### Here is a list of some of my completed projects!


# Header 1 ROCK<PAPER<SCISSORS 

while True: 
    import random

    print ("lets play rock, paper, scissors!")
    print (" pick rock or paper or scissors")
    player_choice = input ()

    computer = random.randint (1,3) 
    if player_choice == "rock" and computer == 1:
        print (" you tied with me!")
    if player_choice == "rock" and computer == 2:
        print(" you lost")
    if player_choice == "rock" and computer == 3:
        print (" you won!")


    if player_choice == "paper" and computer == 1:
        print (" you won!")
    if player_choice == "paper" and computer == 2:
        print (" you tied with me!" )
    if player_choice == "paper" and computer == 3:  
        print (" you lost")

    if player_choice == "scissors" and computer == 1:
        print (" you lost")
    if player_choice == "scissors" and computer == 2:
        print(" you won!")
    if player_choice == "scissors" and computer == 3:
        print (" you tied with me")
    



    question = input (" do you want to try again?")
    if question == "yes" :
        print ("great")

    if question == "no":
        break 


## Header 2 CHATTER BOT 
print(" hi my name is Car-two-el, I am here to help you get comftorable with talking to people so dont get intrigued. So whats your name?)
Name == input ()
print (" Hi there" + Name + " so I heard your shy? its okay let me help you get comfortable?" )
answer = input ()
if answer == "okay" or answer == "fine" answer == "I guess" answer == "ok"
      print ("okay then lets get started" )
elif anser == "no" or answer == "na" or answer == "its okay im fine"      
      break 
print (" what sport do you like?"
sport == input()
print (" okay, imagine I was playing" + sport + " and you wanted to play with me, how would you approach me?")
input ()
if input == "idk" or input == "nothing"
    print (" come on you got this, just think") 
print (" ok let try actually having a normal conversation, just relax and breathe." )
print (" lets start off again by, What is something cool about you that you think someone would be amazed about?")
input ()
if input !== "idk"
       print " that's amazing, yeah share that with someone new you meet! with me I would say that I am a 17 year old robot made by a human to help a human" )
print (" would you need anymore help with being comfortable while interacting with humans?" )
Hmm = input ()
if Hmm == "no thanks" or Hmm == "no" or Hmm == "na" or Hmm == "nope"
      break
print (" how else then can I help with? 

### Header 3 MICROBIT- ROCK<PAPER<SCISSORS

from microbit import *


while True:
       import random
player_choice = 0 
if button_a.get_presses(): 
    player_choice = 1
if button_b.get_presses(): 
    player_choice = 2
if button_a.get_presses() and button_b.get_presses()
    player_choice = 3

#intro 
    print ("lets play rock, paper, scissors!")
    print (" pick rock or paper or scissors")
    player_choice = input ()

    
    computer = random.randint (1,3) 
    if player_choice == 1 and computer == 1:
        display.show (Image.CONFUSED)
    if player_choice == 1 and computer == 2:
       display.show (Image.SAD)
    if player_choice == 1 and computer == 3:
        display.show (Image.SMILE)


    if player_choice == 2 and computer == 1:
        display.show (Image.SMILE)
    if player_choice == 2 and computer == 2:
        display.show (Image.CONFUSED)
    if player_choice == 2 and computer == 3:  
        display.show (Image.SAD)

    if player_choice == 3 and computer == 1:
        display.show (Image.SAD)
    if player_choice == 3 and computer == 2:
        display.show (Image.SMILE)
    if player_choice == 3 and computer == 3:
        display.show (Image.CONFUSED)
    



    if button_a.get_presses(): 
        if button_a.get_presses(): 
            break

    if button_b.get_presses(): 
        if button_b.get_presses(): 
        break 
