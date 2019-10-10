#slow typing
import sys,time
def sprint(str):
   for c in str + '\n':
     sys.stdout.write(c)
     sys.stdout.flush()
     time.sleep(3./90)

#clear function + print
from os import system, name 
from time import sleep 
def clear(): 
    if name == 'nt': 
        _ = system('cls') 
    else: 
        _ = system('clear')
        
#The first dialogue
sprint("Hi")
time.sleep(2)
sprint("This may sound strange, but you're dreaming right now.")
enter = raw_input("")
sleep(1) 
clear()

sprint("I know, you cannot really belive it, but it's true.")
enter = raw_input("")
sleep(1) 
clear()

sprint("First of all, let me introduce myself:")
sleep(2)
sprint("I am you, from the future.")
enter = raw_input("")
sleep(1) 
clear()

