# odd-and-even-numbers
#Program to determine whether a number is even or not

x = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]

for i in range(20,41):
    x.append(i)

def __even(x):
    for i in x:
        y = i % 2 == 0
        print(i,y)
        if y == True:
            print("This is an even number.")
        if y == False:
            print("This is an odd number.")
        
__even(x)
