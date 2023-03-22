# Matching-User-Input


name = input("Enter your name ")
print(f"You {name} is going to play with me in this task")

answer = input(f"Are you want to go left or right    ").lower()
if answer == 'left':
    print("You are at the edge of the river.")
    option = input("will you wnat to swim or walk    ").lower()
    if option == 'swim':
        print("you are going to swim in this river. You have to swim for less than 10 minutes")
    elif option == 'walk':
        print(f"{name} You are going to walk around this river which will cost you more time. So be careful for your time")
    else:
        print("I cann't understand you. Pleae try again")
elif answer == 'right':
    option = input(f"{name} You come to a bridge. Will you wnat to cross the brider or back     ").lower()
    if option == 'cross':
        print("You are going to cross this bridge. So be carefull While crossing")
    elif option == 'back':
        print(f"{name} You are going back. Have a safe return")
    else:
        print(f"{name} I cann't understand you. Please try again")
else:
    print("I cann't understand you. please try again")
    
print("you ended the program successfully  ")
print()
