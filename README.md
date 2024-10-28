Printing Hollow Rectangle Star Pattern
In this Python Program, we will be discussing about how to write a program to print Hollow Rectangle Star Pattern. In this pattern, number of rows and numbers of columns are different. Then, User have to enter two value, in which one value will be determine as a number of rows and other value will be considered as columns of the pattern. We can see in this pattern, all stars are present at the boundary of the pattern. And filled with spaces inside the boundary. “For Loop” and “If-Else” Condition will help to print this Hollow Rectangle Star Pattern.

Python Program for Hollow Rectangle Star Pattern​
Working:
Step 1. Start

Step 2. Take number of rows input from the user and store it in any variable (‘rows’ in this case).

Step 3. Take number of coloum input from the user and store it in any variable (‘cols’ in this case).

Step 4. Run a loop ‘i’ number of times to iterate through all the rows. Starting from i=0 to rows.

Step 5. Run a nested loop inside the main loop for printing stars which is starting from j=0 to cols.

Step 6. Inside the above loop print stars only if i==0 or i==rows-1 or j==0 or j==cols-1 in all other cases print a blank space.

Step 7. Move to the next line by printing a new line by using print() function.

Stop 8. Stop

Python Program:
rows = int(input("Enter rows:"))
cols = int(input("Enter Cols:"))

for i in range(0, rows):
    for j in range(0, cols):
        if i==0 or j==0 or i == rows-1 or j == cols-1:
            print("*", end="")
        else:
            print(" ", end="")
    print()
