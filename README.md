# Introduction





n=6
fish = [4,7,0,5,1,2]
max=fish[0]
for i in range(n):
	if fish[i]>max:
		max=fish[i]
print (max)







n=6
fish=[4,6,9,0,3,1]
target=2
have=0
for i in range(n):
	if fish[i]==target:
		have+=1
if have>0:
	print("yes")
else:
	print("no")







numbers = [1,1,3,2,1,5,3,2]
n=len(numbers)
for i in range(0,n):
	times=0
	for j in range(i+1,n):
		if numbers[i]== numbers[j]:
			times+=1
	print(numbers[i],times)










n = 6
fish = [4,3,0,5,1,2]
for i in range(0,n):
    cute=0
    for j in range(0,i):
        if fish[i]>fish[j]:
            cute+=1
    print(cute)











# numbers=[5,6,7,8,9,10]
# total=0
# n=len(numbers)
# for i in range(0,n):
#   total+=numbers[i]
# print(total)









numbers = [5, 6, 7, 8, 9, 10]
n = len(numbers)
for i in range(0, n):
    hf = 0
    for j in range(2, numbers[i]):
        if numbers[i] % j == 0:
            hf = 1
    if hf == 0:
        print(numbers[i])









s = 4.3
steps = 0
current=2
total=0

while total<s:
    steps+=1
    total +=current
    current *=0.98
print(steps)

