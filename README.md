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
Write a code to count the number of words in that file.
### Step 5: 
Run the program.
### Step 6: 
end the program
## PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY :vikash s
## REFERENCE NO :22008879


num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```

## OUTPUT:

#![WhatsApp Image 2023-01-25 at 18 45 36](https://user-images.githubusercontent.com/119433834/214589527-705fa2e9-c48d-4f12-b5d4-8f13ffcc68e9.jpg)


![WhatsApp Image 2023-01-25 at 18 36 21](https://user-images.githubusercontent.com/119433834/214589616-b2a8f320-4f80-416e-9ba1-f21f8d24ef65.jpg)


## RESULT:
Thus the program is written to find the word count from a text.
