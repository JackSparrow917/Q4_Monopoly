# Q4_Monopoly
monopoly

#Jack Sparrow and Liam Morning-Star
#February 21, 2021
#We pledge this program represents our own program code. We recieved ___ help in designing and debugging our program. We spent _30_ minutes so far on this assignment. 

import random

def main():
    startmoney = 15000
    while True:
        players = int(input("How many players are playing? 2-4 "))
        if players == 2:
            player1 = input("What is player one's name? ")
            player2 = input("What is player two's name? ")
            break
        elif players == 3:
            player1 = input("What is player one's name? ")
            player2 = input("What is player two's name? ")
            player3 = input("What is player three's name? ")
            break
        elif players == 4:
            player1 = input("What is player one's name? ")
            player2 = input("What is player two's name? ")
            player3 = input("What is player three's name? ")
            player4 = input("What is player four's name? ")
            break
        else:
            print("Please enter either 2, 3, or 4.")
            
    def first():
        print('A person will be chosen randomly to see who goes first...') 
       if players == 2:
            roll = random.randint(1, 2)
            if roll == 1:
                print(player1 + ' goes first.')
            elif roll == 2:
                print(player1 + ' goes first.')
            
        if players == 3:
            roll = random.randint(1, 3)
            if roll == 1:
                print(player1 + ' goes first.')
            elif roll == 2:
                print(player2 + ' goes first.')
            elif roll == 3:
                print(player3 + ' goes first.')
          
        if players == 4:
            roll = random.randint(1, 4)
            if roll == 1:
                print(player1 + ' goes first.')
            elif roll == 2:
                print(player2 + ' goes first.')
            elif roll == 3:
                print(player3 + ' goes first.')
            elif roll == 4:
                print(player4 + ' goes first.')
        
    first()
        
    def board():
        print('hello')
    board()
    def board1():
        pass
    board1()
    def board2():
        pass
    board2()
    def board3():
        pass
    board3()
    def board4():
        pass
    board4()

    
    def bank():
        bank = money + 15000
        
    bank1()
    def bank2():
        pass
    bank2()
    def bank3():
        pass
    bank3()
    def bank4():
        pass
    bank4()
    
    
    
    def communitychest():
        pass
    communitychest()
    def chance():
        pass
    chance()

    def jail():
        pass
    jail()


    
    def trade():
        pass
    trade()

    def bankruptcy():
        pass
    bankruptcy()

    def roll():
        pass
    roll()

    def go():
        pass
    go()
main()
