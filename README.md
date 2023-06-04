# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Assign value for num_word

### Step 2: 
Open the file in read mode.
 
### Step 3: 
Iterate using for loop.

### Step 4:  
Increment the word with length of the word.

### Step 5: 
Print the number of words in text.

## PROGRAM:
```
'''
Program to count the words in a file
Devoloped by: HARISH RAGAV S
Register Number: 212222110013
'''
fname=input("Enter thr file name: ")
num_words = 0

with open(fname,'r') as f:
  for line in f:
    words = line.split()
    num_words+=len(words)
print('Number of words: ',num_words)
```

### OUTPUT:
![image](https://github.com/harishragav272003/Word-count/assets/119345345/51268d12-b7c4-4d9a-b65c-9b9257fd01d9)


## RESULT:
Thus the program is written to find the word count from a text.
