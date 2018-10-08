
1. Write a program which accepts a sequence of comma-separated numbers from console and
generate a list.


```python
x = input("Type comma seperated input values:")
```

    Type comma seperated input values:1,2,3,4,5,A,B,C,D
    


```python
lst = x.split(",")
```


```python
print("list output", lst)
```

    list output ['1', '2', '3', '4', '5', 'A', 'B', 'C', 'D']
    

2. Create the below pattern using nested for loop in Python.



```python
i = range(0,5,1) 
j = range(5,0,-1)

for x in i:
    for y in range(x):
        print("*",end="")
    print("")  
for x in j:
    for y in range(x):
        print("*",end="")
    print("")   
```

    
    *
    **
    ***
    ****
    *****
    ****
    ***
    **
    *
    

3. Write a Python program to reverse a word after accepting the input from the user.


```python
"KAMALAKANNAN"[::-1]
```




    'NANNAKALAMAK'


