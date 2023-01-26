# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC, Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open Jupyterlab and a plain text file and save the file with .txt extension

### Step 2:
Enter some words in file.txt file.

### Step 3:
Create python notebook.

### Step 4:
Enter the code with file name as excatly given in .txt extension.

### Step 5:
Run the code ,it will copy from file to file2

### Step 6:
Open the file2.txt it will copy the input and display.



## PROGRAM:
```
#Developed by: S Kantha Sishanth
#Reference no: 22007660

with open('file01.txt','r') as f1:
    with open('file02.txt','a') as f2:
        for line in f1:
            f2.write(line)
```

### OUTPUT:
#### file01:
!['file01'](https://github.com/Skanthasishanth/copy-file/blob/main/file01.png)

#### file02:
!['file02'](https://github.com/Skanthasishanth/copy-file/blob/main/file02.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
