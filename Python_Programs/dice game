# this is my dice game

import random

ai = random.randint(1, 6)
me = int(input("Any key between 1 and 4 : "))

a = 0
m = 0

def AI():
  print("AI : " + str(ai))

def ME():
  print("ME : " + str(me))

ME()
AI()

if ai > me:
  print("You lose... you'll do better next!")
  a += 1;
elif ai == me:
  print("draw!")
elif ai < me:
  print("You won!!! You're the best!")
  m += 1;

print("AI score : " + str(a))
print("My score : " + str(m))
