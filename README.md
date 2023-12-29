# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file and write a sentence in it
### Step 2: 
 After that open the file and use read mode to read it
### Step 3: 
Then use .split() bulit-in funtion to split the sentence
### Step 4:  
Then take a variable and give its value equal to zero
### Step 5: 
After that use for loop to find the count of words 
### Step 6: 
At last do function call
## PROGRAM:
```
def count():
    with open("PYTHON2.txt","r") as file:
        a=file.read()
        count=0
        b=a.split()
        for i in b :
            count=count+1
        print(count)
count()
```
### OUTPUT:
![image](https://github.com/Hariveeraprasad-2006/Word-count/assets/145049988/a898cf7d-6f5e-42fa-b6ab-52247aea5bed)
## RESULT:
Thus the program is written to find the word count from a text.
