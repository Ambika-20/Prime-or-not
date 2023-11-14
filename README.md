# Prime-or-not
# To find the entered number is prime or not
x = int(input("Enter a number:"))
if x == 1:
    print("Not a Prime Number")
elif x == 2:
    print("Prime Number")
else:
    for i in range(2, x):
        if x % i == 0:
            print("Not a Prime Number")
            break
    else:
        print("Prime Number")
