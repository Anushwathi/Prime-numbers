# Prime-numbers
num = 29
num = int(input("Enter a number: "))
flag = False
if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    # check for factors
    for i in range(2, num):
        if (num % i) == 0:
            flag = True
            

