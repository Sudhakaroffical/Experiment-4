## NAME: SUDHAKAR K
## REG NO: 212222240107
# Experiment-4

## ARMSTRONG NUMBER 
# Aim: Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program
```python
x = input("Enter a number: ")  
if x.isnumeric():  
    x = int(x)  
    temp = x  
    cube = 0  

    while temp > 0:  
        digit = temp % 10  
        cube += digit ** 3  
        temp //= 10  

    if cube == x:  
        print("Armstrong Number")  
    else:  
        print("Not an Armstrong Number")  
else:  
    print("Enter a Positive Integer.")
```
# Output

![image](https://github.com/user-attachments/assets/9ee804c5-33d4-49bc-802c-747bef9cbd27)

![image](https://github.com/user-attachments/assets/1bed952f-5285-41e1-988f-efec687c874d)

![image](https://github.com/user-attachments/assets/dc47c0c6-3015-40eb-998e-a2c6b47686cb)

![image](https://github.com/user-attachments/assets/6cadb6d9-b8f0-4f32-b9f2-21a3b4fe3109)

![image](https://github.com/user-attachments/assets/58eb5c1f-001d-45e3-91b4-4a8ec49ffbf4)





# Result
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.
