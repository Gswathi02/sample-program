# sample-program
n = input("Enter Number to calculate sum")
n = int (n)
sum = 0
for num in range(0, n+1, 1):
    sum = sum+num
print("SUM of first ", n, "numbers is: ", sum )
