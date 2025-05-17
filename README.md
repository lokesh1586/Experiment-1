## Name: LOKESH M.
## Register Number: 2122224040173

# Experiment-1
##  Write programs in Python Language to demonstrate the working of following constructs with possible test cases: a) do…while b) while…do c)if …else d) switch e) for

## a) Aim
To write python programs for do…while, while...do, if else, for and test with possible test cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
### do...while:
```python
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```
### while...do:
```python
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
### switch:
```python
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    n = input("Enter a value for N: ")  
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")
switch()
```
### if else:
```python
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    try:
        a = int(a)
        b = int(b)
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")
compare()
```
### for:
```python
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")
iterate()
```


## Output
## do...while:
#### 1.Psitive Numbers:
![Screenshot 2025-03-20 104202](https://github.com/user-attachments/assets/a574caeb-1acf-4d19-9c48-b1e8fbbd3ff3)
#### 2.Negative Numbers:
![Screenshot 2025-03-20 104240](https://github.com/user-attachments/assets/b97f052c-db85-42da-8898-3982bc38e49d)
#### 3.Character and String input
![Screenshot 2025-03-20 104314](https://github.com/user-attachments/assets/b353e6a0-59a8-4706-9a55-535805ea886a)
#### 4.Null Input:
![Screenshot 2025-03-20 104329](https://github.com/user-attachments/assets/93d0a4ad-7936-4c89-8fd7-90cd44ba8d00)

## while...do:
#### 1.Psitive Numbers:
![Screenshot 2025-03-20 104856](https://github.com/user-attachments/assets/023dba3b-63a3-4697-afa7-ee45cc687bf6)

#### 2.Negative Numbers:
![Screenshot 2025-03-20 104917](https://github.com/user-attachments/assets/22122ab8-d7b2-4ff2-9a46-d275967c4b70)


#### 3.Character and String input
![Screenshot 2025-03-20 104944](https://github.com/user-attachments/assets/3128c2e7-93eb-41a2-a4c6-e036ffd9fc2d)


#### 4.Null Input:
![Screenshot 2025-03-20 105003](https://github.com/user-attachments/assets/a7456b43-0c92-4dd2-939c-660b6e412a67)


## switch:
#### 1.Psitive Numbers:
![Screenshot 2025-03-20 105214](https://github.com/user-attachments/assets/3b44a29c-3060-474c-8ab3-3d10ffe40646)

#### 2.Negative Numbers:
![Screenshot 2025-03-20 105245](https://github.com/user-attachments/assets/e95f2ad4-26cb-4a26-832a-9632ea5c109b)


#### 3.Character and String input
![Screenshot 2025-03-20 105259](https://github.com/user-attachments/assets/9a71af29-f8cd-47e1-9310-8885bddd14e2)

#### 4.Null Input:
![Screenshot 2025-03-20 105311](https://github.com/user-attachments/assets/17c934d3-3bec-4557-926c-f400fc4c73b8)



## if else:
#### 1.Psitive Numbers:
![Screenshot 2025-03-20 105449](https://github.com/user-attachments/assets/475174da-de28-460e-a3fa-b94155477fd0)

#### 2.Negative Numbers:
![Screenshot 2025-03-20 113422](https://github.com/user-attachments/assets/e0b03acd-17df-4048-a27a-ed8b27fa3076)

#### 3.Character and String input
![Screenshot 2025-03-20 113358](https://github.com/user-attachments/assets/4d7240c3-e0b8-439c-9efa-d4c73c720418)

#### 4.Null Input:
![Screenshot 2025-03-20 105601](https://github.com/user-attachments/assets/e47ada0c-4c25-4750-9360-e16eb6294fe8)


## for:
#### 1.Characters:
![Screenshot 2025-03-20 105706](https://github.com/user-attachments/assets/fc34ec05-6d98-40b8-8551-4bb8c867131b)

#### 2.Numbers:
![Screenshot 2025-03-20 105721](https://github.com/user-attachments/assets/5d2913c6-65e9-4dda-8ce6-f2bafb49e7fe)

#### 3.Null Input:
![Screenshot 2025-03-20 105738](https://github.com/user-attachments/assets/85d2e9ef-37be-47cf-a4d6-3e788dd466a9)



## Result
Thus to write a python program for do…while, while...do, if else and for loop with possible test cases was executed successfully
