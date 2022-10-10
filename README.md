# Ipod-Minigame
This project creates a ui, where the user is able to control their said "ipod" for their own benefits.
This project goes through how to use user inputs and loops in order to make sure that it satisifes the customer needs.

In this project you will see how to use functions 🤖:

def play():
  source = audio.play_file('audio.wav')
  source.paused = False
  while True:
    stop_playback = int(input("Press 2 anytime to stop playback and go back to the menu : "))
    if stop_playback == 2:
      source.paused = True
      return
    else: 
      continue
      
As well as being able to use user inputs 🤖:

userInput = int(input())

Have fun 😀!
     
