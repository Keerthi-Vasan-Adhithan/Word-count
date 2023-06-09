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
'''
 Program to count the number of the words in a file 
 Devoloped by : KEERTHI VASAN A
 Register Number : 212222240048
'''
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

![up1](https://github.com/arhamshajahan/Word-count/assets/127313881/af383a40-fe17-4ec7-9f60-0234ac02a5dd)

![up2](https://github.com/arhamshajahan/Word-count/assets/127313881/2262b99d-f7f1-467c-9c1d-567acf16b14f)


## RESULT:
Thus the program is written to find the word count from a text.
