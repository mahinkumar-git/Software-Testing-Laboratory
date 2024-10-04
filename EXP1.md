# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                           
### REGISTER NUMBER : 212222040094

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 
```python
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```python
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```



### iii.) switch 
```python
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```



### iv.) if else
```python
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 
compare()
```



### v.) for
```python
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```


### Output:
### i.)do…while: 
![Screenshot From 2024-10-04 10-17-37](https://github.com/user-attachments/assets/0f7064f3-8c20-45f5-b655-43cf35214fd9)



### ii.) while..do:
![Screenshot From 2024-10-04 10-20-54](https://github.com/user-attachments/assets/8234bea2-16ec-49d7-b64b-58537d439082)



### iii.) switch 
![Screenshot From 2024-10-04 10-24-52](https://github.com/user-attachments/assets/67ea59e8-4a36-4fa8-b995-db187794ba0e)



### iv.) if else
![Screenshot From 2024-10-04 10-28-30](https://github.com/user-attachments/assets/54a91e87-4c07-4f5e-8a51-8a5efff29252)



### v.) for 
![Screenshot From 2024-10-04 10-33-44](https://github.com/user-attachments/assets/9fdf49ca-1a49-47e5-8755-fbc444da940f)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.

