# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Create a file and add some content into it.

Step 2: Open file using with keyword/built-in function in read mode.

Step 3: Use read() to read the contents of the file.

Step 4: Split the lines using split().

Step 5: Iterate the list and increment the count

Step 6: Print the output . 

## PROGRAM:
```python
#Program to find number of words
#Developed by: S.S.Sriram
#RegisterNumber:22004880
num = 0
with open('MyFile.txt','r') as f1:
  for i in f1:
    word =i.split()
    num += len(word)
print("NUMBER OF WORDS =",format(num))
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/120554177/215003025-f3035d50-28d6-4989-8295-5362e097f821.png)



## RESULT:
Thus the program is written to find the word count from a text.
