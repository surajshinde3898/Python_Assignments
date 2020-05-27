#1 Find max of three number 

def max_num(num1,num2,num3):

    return max(num1,num2,num3)
    
N=max_num(2,4,8)

print(N)


#2 Program to detect the number of local variable declared in a function.

def count_localvar():

    s=12
    
    u=30
    
    r=25
    
print("no. of local variable:",count_localvar.__code__.co_nlocals)    


#3 write a recursive fuction to calculate the sum of numbers from 0 to 10.

def sum_digit(num):

    if num<=0:
    
        return num
        
    return num + sum_digit(num-1)
    
num = 10

print(sum_digit(num))


#4 create a fuction showStudent() in such a way that it should accept student id , name and its college name
#  is missing in function call it should show it as by default id is 1 and college name is vita.


def showStudent(name ,student_id=1, college_name='Vita'):

    print(student_id , name , college_name)

showStudent('suraj')    


#5 write a fun. that takes a list and return a new list with unique elements of the list.

def unique_list(l1):

    print("List",l1)
    
    l2 = set(l1)
    
    return l2

l1 =[]

N= int(input("enter no of elemet"))

for i in range(0,N):

    ele = int(input("Enter element"))
    
    l1.append(ele)

N=unique_list(l1)

l = list(N)

l.sort()

print("Unique List",l)


#6 write a program to obtain the sum of the FIRST and LAST digit of this number

def sum_of_digit(num):

    for i in range(0,len(num)):
    
        sum1 = int(num[0])+ int(num[-1])
        
        return(sum1)
    
print(sum_of_digit(input("Enter Number")))    











