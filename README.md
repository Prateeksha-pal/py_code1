#A program for guessing a number
print("Welcome to the number guessing game")
print("The number of chances in this game are 10:\nBe Careful")
i=0
while i<10:
     i=i+1
     print("The chance no is:",i)
     inp=int(input())
     if i<10:
     	print("Now the number of chances are",10-i)
     	if inp<55:
     		print("Hint:Enter a greater number\v")
     	elif inp>55:
     		 	print("Hint:Enter a smaller number\v")
     	else:
        	 print("Congratulations ,you entered the correct number\v")
        	 break
     if i==10 and inp!=55:
     	print(" you lost the game")
     else:
     	print("you won the game")
print("See you again")
