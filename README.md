'''
Write a program to create a list and display it. 
Input format:
Input consist of n+1 integers
First integer corresponds to the size of the list
Next n inputs corresponds to the elements in the list 

 def create_and_display_list():
   
    n = int(input("Enter the size of the list: "))
    
 
    result_list = []
    
  
    for _ in range(n):
        element = int(input())
        result_list.append(element)
    
    print(result_list)


create_and_display_list()
'''
Write a program to create a list and display it. 
Input format:
Input consist of n+1 integers
First integer corresponds to the size of the list
Next n inputs corresponds to the elements in the list 

4 
1
2
3
4
Output
1 2 3 4
'''
Write a Python Program to find the largest number in a list
Input & Output Format:
Input consists of one list and one integer.
First input consists of a size of a list.
Second inputs corresponds to the size of the list.
Output consists of the largest element.

def find_largest_number(numbers):
    return max(numbers)


if __name__ == "__main__":
   
    size = int(input("Enter the size of the list: "))
    
   
    numbers = []
    
   
    print("Enter the elements of the list:")
    for _ in range(size):
        num = int(input())
        numbers.append(num)
    
   
    largest_number = find_largest_number(numbers)
    print(largest_number)
'''
Write a Python Program to put the even and odd elements in a list into two different lists.
def separate_even_odd(numbers):
    even_list = []
    odd_list = []
    
    for num in numbers:
        if num % 2 == 0:
            even_list.append(num)
        else:
            odd_list.append(num)
    
    return even_list, odd_list


if __name__ == "__main__":
  
    size = int(input("Enter the size of the list: "))
    
  
    numbers = []
    

    print("Enter the elements of the list:")
    for _ in range(size):
        num = int(input())
        numbers.append(num)
    
   
    even_list, odd_list = separate_even_odd(numbers)
    
  
    print("The even list:", even_list)
    print("The odd list:", odd_list)

'''
Write a program to find the sum of the elements in the array. 
Input Format: 
Input consists of n+1 integers where n corresponds to the number of elements in the array.
The first integer corresponds to n and the next n integers correspond to the elements in the array.
Assume that the maximum number of elements in the array is 20. 
def calculate_mean(elements):
    return sum(elements) / len(elements)


if __name__ == "__main__":
    
    n = int(input("Enter the number of elements: "))
    
    
    elements = []
    
   
    print("Enter the elements of the array:")
    for _ in range(n):
        element = int(input())
        elements.append(element)
    
    
    mean = calculate_mean(elements)
    
    
    print(f"The mean of the array is: {mean:.2f}")
    '''
    Write a Python Program to find the smallest number in a list
Input & Output Format:
Input consists of one list and one integer.
First input consists of a size of a list.
Second inputs corresponds to the size of the list.
Output consists of the largest element

def find_smallest_number(numbers):
    return min(numbers)


if __name__ == "__main__":
    
    size = int(input("Enter the size of the list: "))
    
 
    numbers = []
    
   
    print("Enter the elements of the list:")
    for _ in range(size):
        num = int(input())
        numbers.append(num)
    
    
    smallest_number = find_smallest_number(numbers)
    print(smallest_number)

'''
Write a program to count the number of times the given value is repeated.
Input Format:
First line of input consists of our list elements.
Second line of input consists of value to count.
if __name__ == "__main__":
    
    elements = input("Enter the list elements separated by spaces: ").split()
    
 
    elements = [int(num) for num in elements]
    

    value_to_count = int(input("Enter the value to count: "))
    
    count = elements.count(value_to_count)
    
 
    print(count)




