# 02-03-2022-assignment-1
#program to subtract of two matrices.
a=[]
m=int(input('enter the no. of rows: '))
n=int(input('enter no. of columns: '))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    a.append(row)
print(a)
b=[]
m=int(input('enter the no. of rows: '))
n=int(input('enter no. of columns: '))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    b.append(row)
print(b)
result=[[0,0],[0,0]]
for i in range(m):
    for j in range(n):
        result[i][j]=a[i][j]-b[i][j]
print('resultant matrix is: ')
for i in range(m):
    for j in range(n):
        print(result[i][j],end=' ')
    print()
