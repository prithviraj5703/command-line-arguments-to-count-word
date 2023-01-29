# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 Open file using open().
### Step 3: 
Use for loopUse len to count number of words.
### Step 4:  
Use len to count number of words.
### Step 5: 
Give print.
### Step 6: 
End of the program
## PROGRAM:
```python
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![command line argument](https://user-images.githubusercontent.com/121418418/215334240-a1d05b72-1d22-4630-b9c6-fdc5f8455fa4.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
