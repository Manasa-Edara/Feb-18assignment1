#PROGRAM TO PRINT COUNT OF N PRIME NUMBERS
def isprime(n):
    for i in range (2,n):
        if n%i==0:
            return False
        return True 
n=int(input('enter n:'))
count=0
for i in range(2,n+1):
    if isprime(i):
        count=count+1
        print(i,end=' ')
        print(count)

OUTPUT:
enter n:10
3    1
5    2
7    3
9    4
