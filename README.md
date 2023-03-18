# Dice-simulator
Rool Dice
    
    import random
    x='y'
    while x=='y':
        x=input("press 'y ' for rool again and 'q' for quit :" )
    
        number=random.randint(1,6)
        if x=='q':
            break
        elif number==1:
            print("[       ]")
            print("[   0   ]")
            print("[       ]")
        elif number==2:
            print("[0      ]")
            print("[       ]")
            print("[      0]")
        elif number==3:
            print("[0      ]")
            print("[   0   ]")
            print("[      0]")
        elif number==4:
            print("[0     0]")
            print("[       ]")
            print("[0     0]")
        elif number==5:
            print("[0     0]")
            print("[   0   ]")
            print("[0     0]")
        elif number==6:
            print("[0     0]")
            print("[0     0]")
            print("[0     0]")
    
    
