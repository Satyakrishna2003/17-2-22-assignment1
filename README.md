# 17-2-22-assignment1
n=int(input('enter a number:'))
evensum=0
oddsum=0
for i in range(1,n+1):
    if i%2==0:
        evensum=evensum+i 
    else:
        oddsum=oddsum+i 
print('sum of even numbers:',evensum)
print('sum of odd numbers:',oddsum)


OUT PUT
enter a number:8
sum of even numbers: 20
sum of odd numbers: 16
