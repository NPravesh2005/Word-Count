# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Import numpy as np

## Step 2: 
 Enter the input values
## Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
## Step 4:  
Run the program
## Step 5: 
Input the values
## Step 6: 
End the program
## PROGRAM:

```python
'''
Developed by : PRAVESH.N
Register no : 212223230154
'''
num = 0
with open("story.txt","r") as f1:
    for i in f1:
         word = i.split()
         num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:

![9th expt](https://github.com/NPravesh2005/Word-Count/assets/164477756/6fc58e4e-8f9d-4ae6-a1bb-78fe67259d3a)


## RESULT:
Thus the program is written to find the word count from a text.
