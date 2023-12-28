# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension.
### Step 2: 
Add some texts in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to count the number of words in that file.

### Step 5: 
Run the program.

### Step 6: 
Display the output.

## PROGRAM:
```
Developed By: SANTHIYA R
Referrence Number: 212223230192
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```

### OUTPUT:
![output](image.png)
![output](image-1.png)

## RESULT:
Thus the program is written to find the word count from a text.
