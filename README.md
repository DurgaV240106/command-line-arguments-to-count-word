# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
 On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
using len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output.
## PROGRAM:
```
fname=input("enter the file name")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:

<img width="579" alt="Screenshot 2024-01-03 010751" src="https://github.com/DurgaV240106/command-line-arguments-to-count-word/assets/144870878/c0a839ce-92de-441a-a3f9-124ea0f52240">


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
