# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file using notepad with extension txt
### Step 2: 
open google colab and mount the drive for using the created file 
### Step 3: 
now open the text file  in read mode
### Step 4:  
then read and split the file using the read() and split() which is assigned to the variable
### Step 5: 
print the assigned variables length using len() funcion
### Step 6: 
end of the program
## PROGRAM:
```
with open('/content/drive/MyDrive/record/content.txt','r') as f:
  a=f.read().split()
  print(len(a))
```
### OUTPUT:
### 1.TEXT FILE:
<img width="663" alt="image" src="https://github.com/Vigneshv-23/Word-count/assets/110780412/d2ff1c55-9932-4e18-bc8d-0858ca18b790">

### 2.MOUNT DRIVE:
![image](https://github.com/Vigneshv-23/Word-count/assets/110780412/6445739b-839c-46dd-809d-5eb54f424f64)

### 3.OUTPUT:
![image](https://github.com/Vigneshv-23/Word-count/assets/110780412/7feb2aca-9506-42bd-83dc-fb76e821e7cf)




## RESULT:
Thus the program is written to find the word count from a text.
