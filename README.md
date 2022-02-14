# Command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.

### Step 2: 
 Use the open() by getting the file name with "sys.argv[1]" which means the first index of given argument
### Step 3: 
Iterate the content of the file using for loop.

### Step 4:  
Split the contents into each line using .split() function

### Step 5: 
Iterate the list of lines and increment the value of variable (word) each time

### Step 6: 
Run the program by giving "python prgm.py EX12.txt" on the terminal.

### Step 7:
End of the Program

## PROGRAM:
~~~
#Program to command line arguments to count word
#Developed by: ANISH M.J
#Register number: 212221230005
import sys
fp = open(sys.argv[1])
count=0
for data in fp:
    l=data.split()
    for i in l:
        count+=1
print("No. of words in the file:",count)
~~~

# OUTPUT:
![output](wordcount.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
