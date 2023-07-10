# CountTheHolidays
# cook your dish here
t=int(input())
while t:
    n=int(input())
    a=list(map(int,input().split()))
    c=0
    for i in range(n):
        if (a[i] not in (6,13,20,27,7,14,21,28)):
            c+=1
    print(8+int(c))
    t-=1
