# Find the Runner-Up Score!
#Runner-Up means, taking second place.
def  runner_up():
	n=int(input("Enter the length: "))
	k=[]
	for i in range(0,n):
		y=int(input("Enter the values: "))
		k.append(y)
	m=max(k)
	while max(k)==m:
		k.remove(max(k))
	print("Runner-Up Score in the list is - ",max(k))
