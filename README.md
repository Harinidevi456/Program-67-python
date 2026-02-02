num =int(input(&quot;Enter the range: &quot;))
for n in range(1,num):
for i in range(2,n):
if(n%i==0):
break

else:
print(n)
output
Enter the range: 10
1
2
3
5
7
