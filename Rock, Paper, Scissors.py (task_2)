import random

rock = '''`
     -------
---'
   -----)
   (-----)
   (-----)
   (----)
--- ,_ _(---)
'`
''
'''

paper = '''`
     -------
 ---'
      ----)----
         ------)
         -------)
         -------)
---
   '--(----------)
   '`
'''

scissors = '''`
     -------
---'
       ----)----
        ------)
    ----------)
    (----)
---
  '--(---)
  '`
'''

game_images = [rock, paper, scissors]

user_choice = int(input("Enter your choice: Type 0 for rock, Type 1 for paper, Type 2 for scissors: "))

if user_choice >= 3 or user_choice < 0:
    print("This is an invalid number, you lose")
else:
    print("You chose:")
    print(game_images[user_choice])
    
    computer_choice = random.randint(0, 2)
    print("Computer chose:")
    print(game_images[computer_choice])

    if user_choice == computer_choice:
        print("It's a draw")
    elif (user_choice == 0 and computer_choice == 1) or \
         (user_choice == 1 and computer_choice == 2) or \
         (user_choice == 2 and computer_choice == 0):
        print("You lose")
    else:
        print("You win")
