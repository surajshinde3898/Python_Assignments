#1

print("Number which are  divisible by 7 and not multile of 5::")

for i in range(2000,3200):

    if i%7==0 and i%5!=0:
    
        print(i,',',end='')

#2

dict1= {}

n= int(input("Enter a number of inputs"))

dict1 = {i:i*i for i in range(1,n+1)}

print(dict1)


#3

while True:

    S = input("Enter String ")
    
    print(S.upper())


#4

N =  int(input("Enter Number"))

if N%2==0:

    print("Even")
    
else:

    print("Odd")


#5

Age = int(input('Enter Your Age'))

if Age in range(8,13):

    print("You are allowed... Welcome")
    
else:

    print("Sorry not allowed... Bye")
