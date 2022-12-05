# sum-of-all-digits-in-a-number
n=int(input('Enter any given number:'))
sum=0
while(n>0):
    sum=sum+(n%10)
    n=n//10
print('The sum of its digits is',sum)
