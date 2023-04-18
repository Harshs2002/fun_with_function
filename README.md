# fun_with_function

def add(numbers):             # using function here named add
    """Give the sum of all the numbers in a list"""
    sum = 0
    for number in numbers:
        sum += number         # storing the added values in sum
    return sum
my_list = [8,2,3,0,7]         #creating the our list
print(add(my_list))           # printing our list ==> sample input = (8,2,3,0,7) == (8+2+3+0+7)
                                                      #output = 20
