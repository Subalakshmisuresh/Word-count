# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a txt file to count the number of word in that file.

### Step 2:Open the txt file in read mode using open().
 
### Step 3:Using split() function to split the words in the txt file and count it

### Step 4:Run the python program to get the output.

### Step 5:Number of words in the txt file is displayed as the output.

## PROGRAM:

Developed by : SUBALAKSHMI.S

Register Number : 212222100051

```py
fname = input('Enter file name: ')
num_words=0
with open(fname,'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Number of words: ',num_words)
```
### OUTPUT:

![image](https://github.com/Subalakshmisuresh/Word-count/assets/121957896/7e96187c-f8ab-43b3-91a2-6af4a141be73)


![image](https://github.com/Subalakshmisuresh/Word-count/assets/121957896/136eb8e7-888e-4df8-9457-fb29a5a54374)


## RESULT:
Thus the program is written to find the word count from a text.



