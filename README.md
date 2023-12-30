# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create the file.
### Step 2: 
Write few lines in that file.
 
### Step 3: 
Create a python file
### Step 4:  

Write a code to copy the content of the file to new file.

### Step 5: 
Run the program.

### Step 6: 
display the output.

## PROGRAM:
```
with open("text1.txt",'r') as fp:
     msg1=fp.read()
with open("copytxt",'w') as fp1:
     fp1.write(msg1)
```

### OUTPUT:

![Alt text](<Screenshot 2023-12-30 103544.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.