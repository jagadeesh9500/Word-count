# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3:
Read the file using read() method.
### Step 4:
Use split() method to split the file content into words.
### Step 5:
Use len() to find the total words.
### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM:
```
# program to find the number of words in a text file
# Developed by :JAGADEESH P 
# Register number : 23013534
num=0
with open("file.txt","r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("The number of words are in the file is",num)
```

### OUTPUT:
![image](https://github.com/jagadeesh9500/Word-count/assets/149087921/b8fed4f3-7324-48be-92bf-8c55c99e7345)



## RESULT:
Thus the program is written to find the word count from a text.
