Variable
CONCEPT: A variable is a name that represents a value stored in the computer’s memory.
A variable is a name that represents a value in the computer’s memory. 

Creating Variables with Assignment Statements
Eg:  age = 25

An assignment statement is written in the following general format:
variable  = expression
After an assignment statement execute, the variable listed on the left side of the = will reference the value given on the right side of =.

width = 10
length = 5 

print (width)→ 10
print (“width”) → width    #有引號→顯示文字，沒有引號→顯示數字

variable 一定會出現在 =左邊
25 = age 
>>>syntaxError: can’t assign to literal

Variables Naming Rules:
(1)不能使用python關鍵字
(2)variable不能含括space
(3)第一個字必須是英文字(大、小寫都可)
(4)第一個必須是數字
(5)uppercase和lowercase都可被接受
Eg:  ItemsOrdered和itemsordered 是兩個不同的variable

![image](https://github.com/itsmewm17/Python-Note/assets/166125320/1940a0a1-7a5a-46e6-9059-1e229ec70688)


Variables Reassignment
![image](https://github.com/itsmewm17/Python-Note/assets/166125320/b4b0a36e-cc32-4083-8216-e8bd24a7f7b3)
![image](https://github.com/itsmewm17/Python-Note/assets/166125320/4aa67d95-d4be-4fb8-8675-039ead724de7)
![image](https://github.com/itsmewm17/Python-Note/assets/166125320/fc36d9fc-870d-49f3-b1d9-665f6267e007)
Python uses data types to categorize values in memory. When an integer is stored in memory, it is classified as an int, and when a real number is stored in memory, it is classified as a float. 
#它可以是整數或浮點數
It determines the data type according to the following rules:
(1)整數：如7, 124, -4
(2)浮點數(float)：如1.5, 3.14, 5.0

<class “int”> → 代表將數字無條件捨去至最近的整數
<class “float”> → 代表將數字為浮點數
假如想顯示currency符號，則應寫為 print (“$” + str(123))




