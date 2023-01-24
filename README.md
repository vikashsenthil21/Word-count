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
def program():
    count=0
    with open("exp1.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```
### OUTPUT:

![Screenshot 2023-01-24 232528](https://user-images.githubusercontent.com/119433834/214372905-b86925da-5f9c-4b26-a3bd-ebff15d689fd.png)


![Screenshot 2023-01-24 232452](https://user-images.githubusercontent.com/119433834/214372919-860d6ff2-af7a-40f9-a3cb-2d76b83dd65d.png)


## RESULT:
Thus the program is written to find the word count from a text.
