# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys.
### Step 2: 
Open the file as f1.
### Step 3: 
read the file using read() and assign to the variable data.
### Step 4:  
split the data(data.split()).
### Step 5: 
Print the word count using len(word).
### Step 6: 
Close the file.
## PROGRAM:
```PYTHON
#python program for word count
#developed by : NIKSHITHA G
#reference number: 23007784
import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```

### OUTPUT:
![Alt text](<word count.png>)
## RESULT:
Thus the program is written to find the word count from a text.
