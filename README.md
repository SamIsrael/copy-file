# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a text file in read mode.

### Step 2: 
Open another file in append mode.
 
### Step 3: 
Using for loop append the text in the first file to the second file


## PROGRAM:
```Python
with open("merge.txt",'r') as f1:
    with open("merge2.txt",'a') as f2:
        for line in f1:
            f2.write(line)

```

### OUTPUT:

![image](./mg.png)
![image](./mg1.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.