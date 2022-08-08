# Sum-of-numbers-from-m-to-n
# Get the initial(m) and final(n) values from the user
m = int(input("Enter the value of m:"))
n = int(input("Enter the value of n:"))
s = 0
while(m<=n):
    s = s+m
    m = m+1
    print("Sum of numbers from",m,"to",n,"=",s)
