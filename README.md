# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.
### Step 2: 
 Pass the filename as the first argument.
### Step 3: 
Open the file as sys.argv[1]
### Step 4:  
Read th file using read() method.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to dermine number of words.
## PROGRAM:
```
'''
DEVELOPED BY:S.Sanjay Balaji
REGISTER NUMBER:23005804
'''
import sys
file=open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![image](https://github.com/SanjayBalaji0/command-line-arguments-to-count-word/assets/145533553/9f07f8de-453e-471f-af66-dcfe5f4cc8ce)

![image](https://github.com/SanjayBalaji0/command-line-arguments-to-count-word/assets/145533553/7426cf1b-0b81-4782-ad28-22cef0afb9fe)

![image](https://github.com/SanjayBalaji0/command-line-arguments-to-count-word/assets/145533553/621a57ac-7a07-40ef-ada5-937bba93f9c8)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
