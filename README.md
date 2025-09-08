## NAME: SRIRAM S
## REGNO: 212222240105
# Experiment-3
## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
```python
num = input("Enter a number: ")  
flag = 0  

if num.isnumeric():  
    z = int(num)  

    if z == 2:  
        flag = 1  
    elif z > 2:  
        for i in range(2, z // 2 + 1):  # Loop should include z//2
            if z % i == 0:  
                flag = 0  
                break  
        else:  
            flag = 1  

    if flag == 1:  
        print("Prime Number")  
    else:  
        print("Not a Prime Number")  

else:  
    print("Enter a Positive Number")
```
## Output

![image](https://github.com/user-attachments/assets/8224d524-bd62-4855-a44b-b3a67b41c44f)

![image](https://github.com/user-attachments/assets/fd772f67-f5d8-4b59-8ab1-101ef2194e53)

![image](https://github.com/user-attachments/assets/8f8867a1-1acb-4905-a227-936782bde055)

![image](https://github.com/user-attachments/assets/c20f2883-183b-4493-af5e-6113cbd77634)

![image](https://github.com/user-attachments/assets/f63bd00e-004d-4b59-84c3-9e7d91f90ee7)








## Result
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
