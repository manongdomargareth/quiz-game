# quiz-game

print("Select of your choice subject") print("A. Math") print("B. Science") choice = input("Enter your choice:") print("———————————————————") if choice == 'A':     a = 20     print("Q: What is the sum of 10+10:")     answer = int(input("Your answer is:"))     if answer == a:        print("Correct answer")         print("You've got 5 points")     else:        print("Incorrect answer")         print("You have 0 points")    elif choice == 'B':     b = 'mitochondria'     print("Q: What is the powerhouse of the cell")         answer = input("Your answer is:")     if answer == b:        print("Correct answer")        print("You've got 5 points")     else:        print("Incorrect answer")        print("You have 0 points")    else:     print("Invalid Selection")

