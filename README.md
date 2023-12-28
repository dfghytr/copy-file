# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
```
PC
Anaconda - Python 3.7
```
## ALGORITHM: 
### Step 1:
create a file using a notepad with extension.txt
### Step 2: 
open goole colab and mount the drive for using the created file
### Step 3: 
now open the text file and store the data in variable
### Step 4:  
The read the content in the file and store the data in variable
### Step 5: 
Now open the newuncreated file or an empty file using a different file object by"w+" mode and write the content derieved from file using write().
### Step 6: 
End og the program
## PROGRAM:
```
#To copy a file
#developed by: Abdul kalaam k m
#register number:23005114


f=open("record file.txt","r")
content=f.read()
f1=open("record file updated.txt","w+")
f1.write(content)
print("the content that has been copied to the new file is:",content)
```
### OUTPUT:
![image](https://github.com/23006823/copy-file/assets/138971409/f1f65779-24f7-47cc-ba7d-97421a5055aa)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
