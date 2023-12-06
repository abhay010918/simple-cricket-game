# simple-cricket-game

#  a simple cricket game by ABHAY SINGH

print("Welcome to the cricket ground")
team = input("what is your team name ").lower()
# choosing the faverate team
print("your team name is " + team)
# Now its time to toss
toss = input('Call "head" or "tell".  ').lower()
print("Your call is " + toss)
# toss winner decide the boll or bat
if toss == "head":
    choose = input('You win the toss what will you choose "bat" or "boll". ').lower()
    if choose == "bat":
        print(" You choose to batting first")
        bat = input('What batting style you going to do "tap", "pull", "drive" ').lower()
        if bat == "tap":
            print(" ohh its one run")
        elif bat == "pull":
            print("Boll gose out of the ground to six")
        elif bat == "drive":
            print("Boll gose one tap to boundry thats four")
        else:
            print("Dot ball")
    else:
        print("You have to boll")
        boll = input('what boll you are going to do yourker, spin, short  "yourker", "spin", "short" ').lower()
        if boll == "yourker":
            print("Boll hits the wiket its out")
        elif boll == "spin":
            print("batsman hits drive to its four")
        elif boll == "short":
            print("batsman pull this boll to six")
        else:
            print("Dot boll")
if toss == "tell":
    print("You lose the toss")

print("Thank you for playing this game")
