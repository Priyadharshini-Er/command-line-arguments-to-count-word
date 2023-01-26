# command-line-arguments-to-count-word:
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
Open file using open()
### Step 3: 
Use for loop
### Step 4:  
Use len to count number of words.
### Step 5: 
Print the number of words
### Step 6: 
Give the command to display the number of words
## PROGRAM:
``` python
#Developed by: Priyadharshini.P
#Reference Number: 22008758

import sys
count=0
with open(sys.argv[1],"r") as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("Word count in file=",count)

```
### OUTPUT:
![](./clwc1.png)
![](./clwc2.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
