import random
import time
import sys

def func_bye():
  print("GAME OVER")
  raise SystemExit
  return




def func_level1(): 
  print("------------------------\nSTARTING NEXT LEVEL (1)\n------------------------")
  round_num=1
  while round_num<=5:
    print("------------------------\nRound", str(round_num))
    word=random.choice(WORDS_6)
    time_start=time.time()
    typed=input("TYPE: "+ word+"\nYOU HAVE 10 SECONDS...\n")
    time_end=time.time()
    time_used=time_end-time_start
    if typed==word:
      if time_used<=10:
        round_num+=1
        continue
      break
    break
  return round_num


def func_level2(): 
  print("------------------------\nSTARTING NEXT LEVEL (2)\n------------------------")
  round_num=1
  while round_num<=5:
    print("------------------------\nRound", str(round_num))
    word=random.choice(WORDS_6)
    time_start=time.time()
    typed=input("TYPE: "+ word+"\nYOU HAVE 8 SECONDS...\n")
    time_end=time.time()
    time_used=time_end-time_start
    if typed==word:
      if time_used<=8:
        round_num+=1
        continue
      break
    break
  return round_num


def func_level3(): 
  print("------------------------\nSTARTING NEXT LEVEL (3)\n------------------------")
  round_num=1
  while round_num<=5:
    print("------------------------\nRound", str(round_num))
    word=random.choice(WORDS_6)
    time_start=time.time()
    typed=input("TYPE: "+ word+"\nYOU HAVE 6 SECONDS...\n")
    time_end=time.time()
    time_used=time_end-time_start
    if typed==word:
      if time_used<=6:
        round_num+=1
        continue
      break
    break
  return round_num



def func_level4(): 
  print("------------------------\nSTARTING NEXT LEVEL (4)\n------------------------")
  round_num=1
  while round_num<=5:
    print("------------------------\nRound", str(round_num))
    word=random.choice(WORDS_9)
    time_start=time.time()
    typed=input("TYPE: "+ word+"\nYOU HAVE 6 SECONDS...\n")
    time_end=time.time()
    time_used=time_end-time_start
    if typed==word:
      if time_used<=6:
        word=random.choice(WORDS_9)
        time_start=time.time()
        typed=input("TYPE: "+ word+"\nYOU HAVE 6 SECONDS...\n")
        time_end=time.time()
        time_used=time_end-time_start
        if typed==word:
          if time_used<=6:
            round_num+=1
            continue
          break
        break
      break
    break
  return round_num




def func_level5(): 
  print("------------------------\nSTARTING NEXT LEVEL (5)\n------------------------")
  round_num=1
  while round_num<=5:
    print("------------------------\nRound", str(round_num))
    word=random.choice(WORDS_9)
    time_start=time.time()
    typed=input("TYPE: "+ word+"\nYOU HAVE 6 SECONDS...\n")
    time_end=time.time()
    time_used=time_end-time_start
    if typed==word:
      if time_used<=6:
        word=random.choice(WORDS_9)
        time_start=time.time()
        typed=input("TYPE: "+ word+"\nYOU HAVE 6 SECONDS...\n")
        time_end=time.time()
        time_used=time_end-time_start
        if typed==word:
          if time_used<=6:
            word=random.choice(WORDS_9)
            time_start=time.time()
            typed=input("TYPE: "+ word+"\nYOU HAVE 6 SECONDS...\n")
            time_end=time.time()
            time_used=time_end-time_start
            if typed==word:
              if time_used<=6:
                round_num+=1
                continue
              break
            break
          break
        break
      break
    break
  return round_num



def func_level6(): 
  print("------------------------\nSTARTING NEXT LEVEL (6)\n------------------------")
  round_num=1
  while round_num<=5:
    print("------------------------\nRound", str(round_num))
    word=random.choice(WORDS_9)
    time_start=time.time()
    typed=input("TYPE: "+ word+"\nYOU HAVE 3 SECONDS...\n")
    time_end=time.time()
    time_used=time_end-time_start
    if typed==word:
      if time_used<=3:
        round_num+=1
        continue
      break
    break
  return round_num






WORDS_6=["mother", "laptop", "people", "buried", "phones", "letter", "happen", "giant", "mason", "house", "money", "table", "juicy", "dirty"]

WORDS_9=["abjointed", "antiworld", "importance", "deliverance", "decrease", "increase", "disorganized", "unbelievable", "misunderstanding", "hopelessness", "beliefs", "tradition", "religion", "achievement", "unprecedented", "inhumane", "insanity", "disapproval", "hypocrisy", "babaric", "hippopotamus", "flabbergasted", "originated"]



print("This is a typing game that tests how fast you can type a word")
str_start=input("Are you ready?! (yes/no)")
if str_start=="yes":

  round_num = func_level1()
  while round_num!=6:
    func_bye()

  round_num = func_level2()
  while round_num!=6:
    func_bye()

  round_num = func_level3()
  while round_num!=6:
    func_bye()

  round_num = func_level4()
  while round_num!=6:
    func_bye()

  round_num = func_level5()
  while round_num!=6:
    func_bye()

  round_num = func_level6()
  while round_num!=6:
    func_bye()

  print("YOU'VE COMPLETED ALL LEVELS \n YOU'RE A GENIUS!!")

else:
  func_bye()

