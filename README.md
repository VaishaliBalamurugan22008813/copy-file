# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read
mode

### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file
### Step 6: 
End the program
## PROGRAM:
```
Developed by: VAISHALI BALAMURUGAN
RegisterNumber: 22008813
with open("sample1.txt", "r") as firstfile:
with open("sample2.txt", "a") as secondfile:
for line in firstfile:
secondfile.write(line)
```
### OUTPUT:
SAMPLE1.TXT :
![S1](https://user-images.githubusercontent.com/119390134/213963389-e436226c-7812-42a6-a951-dbbc37369a06.png)

SAMPLE2.TXT :

![S2](https://user-images.githubusercontent.com/119390134/213963561-1495493b-c9b1-4882-bedf-a787773d0d4d.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
