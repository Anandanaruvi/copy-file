# copy-file

## AIM:

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM:

### Step 1:

Open the first text file and read it.

### Step 2:

After that open the second text file and append the first one to it.

### Step 3:

Start the for loop.

### Step 4:

Then write the lines from the first one to the second file using the write function.

### Step 5:

Print the output

## PROGRAM:

with open("text.txt") as f:
    with open("text1.txt","w") as f1:
        for line in f:
           f1.write(line)

### OUTPUT:

![copy](https://user-images.githubusercontent.com/120443233/215515148-f84c5916-484a-47a1-a81e-df62902d603a.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
