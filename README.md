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

![Screenshot 2023-01-24 232452](https://user-images.githubusercontent.com/119433834/214372228-6a37460c-3f9f-4849-99b7-3dacbc97818a.png)


![Screenshot 2023-01-24 232258](https://user-images.githubusercontent.com/119433834/214372292-f7e10674-9c1d-4d39-8952-3b8466185daf.png)



## RESULT:
Thus the program is written to find the word count from a text.
