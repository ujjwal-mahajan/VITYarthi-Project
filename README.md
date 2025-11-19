# VITYarthie-Project
A Python program that takes a number 'n' as input from user, and prints the numbers from 0,1,2,....,n. But the numbers from 10 occurs uniquely so each number is considered, like 1,0,1,1,1,2,.... 

n = int(input("Enter a number: "))

result = ""
i = 1

while len(result) < n:
    result += str(i)
    i += 1

result = result[:n]

print(result)
