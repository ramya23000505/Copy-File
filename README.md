# Copy-File
## Date:
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file named "hello.txt" in read mode and assign its file pointer to the variable fp.
### Step 2: 
 Open the file named "myfile.txt" in write mode and assign its file pointer to the variable fp1.
### Step 3: 
Read the entire content of "hello.txt" using the file pointer fp and store the content in the variable data.
### Step 4:  
Write the content stored in data to the file "myfile.txt" using the file pointer fp1.
### Step 5: 
Close the file pointer fp to release the resources associated with "hello.txt".
### Step 6: 
Close the file pointer fp1 to release the resources associated with "myfile.txt".
## PROGRAM:
```
Developed By: RAMYA R
Register Number: 212223230169
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("hello.txt","myfile.txt")
```
### OUTPUT:
![alt text](<Screenshot 2024-05-15 165442.png>)
![alt text](<Screenshot 2024-05-15 165928.png>)
![alt text](<Screenshot 2024-05-15 165934.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
