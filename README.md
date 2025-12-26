# Print-Odd-Numbers-in-Reverse-Order-

n=int(input("enter the limit"))
if n%2==0:
    for i in range(n-1,0,-2):
        print(i)
else:
    for i in range(n,0,-2):
        print(i)
Output:
enter the limit3
3
1
