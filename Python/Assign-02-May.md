# 1. Write a NumPy program to get the numpy version and show numpy build configuration.
import numpy as np

print(np.__version__)

print(np.show_config())


# 2. Write a NumPy program to test element-wise for complex number, real number of a given array. Also test whether
# a given number is a scalar type or not.

Array = ([2+3j,5,9.8,2-8j,4])

print(Array)

print(np.iscomplex(Array))

print(np.isreal(Array))

print(np.isscalar(Array))


# 3. Write a NumPy program to test whether none of the elements of a given array is zero.

y = ([3,0,5,0,7,8])

print(np.all(y))


# 4. Write a NumPy program to test whether any of the elements
# of a given array is non-zero.

x = np.array([3,4,6,8,6,0,5,4,0])

print(np.any(x))


# 5. Write a NumPy program to test element-wise for NaN of a given array

a = np.array([5,3,1,0,np.NaN])

print(np.isnan(a))


# 6. Write a NumPy program to create an element-wise comparison
# (greater, greater_equal, less and less_equal) of two given arrays.

Array1 = np.array([5,6])

Array2 = np.array([5,9])

print(np.greater(Array1,Array2))

print(np.greater_equal(Array1,Array2))

print(np.less(Array1,Array2))

print(np.less_equal(Array1,Array2))


# 8. Write a NumPy program to create an array with the values 1, 7, 13, 105
# and determine the size of the memory occupied by the array.

s = np.array([6,5,7,8,4,3])

print("%d" %(s.size*s.itemsize))


# 9. Write a NumPy program to create an array of 10 zeros, 10 ones, 10 fives.

arr = np.zeros(10)

print(arr)

arr = np.ones(10)

print(arr)

arr = np.ones(10)*5

print(arr)


# 10. Write a NumPy program to create an array of the integers from 30 to 70.

z = np.arange(30,71)

print(z)


# 11. Write a NumPy program to create an array of all the even integers from 30 to 70.

z = np.arange(30,71,2)

print(z)


# 12. Write a NumPy program to create a 3x3 identity matrix

a = np.identity(3)

print(a)


# 13. Write a NumPy program to generate a random number between 0 and 1.

num = np.random.normal(0,1)

print(num)


# Q14

num = np.random.normal(0,1,15)

print(num)


# 15

Array = np.arange(15,55)

print(Array[1:-1])












































