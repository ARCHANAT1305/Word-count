# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Set num to 0. This variable will be used to store the total number of words in the file.
### Step 2: 
 Use the with open statement to open the file named "sample.txt" in read mode ("r").
### Step 3: 
 Use a for loop to iterate over each line in the file
### Step 4:  
Split each line into words using the split() method.
### Step 5: 
Add the length of the list of words to the num variable.
### Step 6: 
After processing all lines in the file, print the total word count.
## PROGRAM:
```
Developed By: ARCHANA.T
Register Number :212223240013
num=0
with open("word count.txt","r") as f1:
    for i in f1:
        word = i.split()
        num+=len(word)
print("The number of words are in the file is ",num)       
```
### OUTPUT:
![word count](https://github.com/ARCHANAT1305/Word-count/assets/145975189/04948f4d-702f-4872-a371-544091194cb4)




## RESULT:
Thus the program is written to find the word count from a text.
