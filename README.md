# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.
### Step 2: 
Open the required file by using the function "with".
### Step 3: 
Then use the laptop to assign the i value in the file.
### Step 4:  
Using split function to spilt the words.
### Step 5: 
Finding the given length of the words by using len() fuction.
### Step 6: 
Calling the function and Printing the number of words.
## PROGRAM:
```
#Program to count the no. of words in a file.
#Developed by: Gnanendran N
#Register Number: 23006661
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```
### OUTPUT:
![Exp5a](https://github.com/GnanendranN/Word-count/assets/138955207/2099c880-d6cf-4e42-996f-547523a34325)
![Exp5aoutput](https://github.com/GnanendranN/Word-count/assets/138955207/6276590b-62c7-4bd8-b3dd-006eefc85755)



## RESULT:
Thus the program is written to find the word count from a text.
