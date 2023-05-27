Q1.-> Python can be used for various purposes from backend development to building data pipelines and cloud computing, it is very easy to use and can be used on multiple platform using PVM python virtual machine hence its called a general purpose high-level programing language.

Q2.-> Unlike other languages we do not need to declare data-type for the value before compilation, python stores that value at some memory location and then binds that variable name to that memory container which makes the contents of the container accessible through that variable name and the data-type is only known at runtime, hence python is called a dynamically typed language.

Q3.-> Advantages of Python
	1. Easy to use.
	2. Interpreted Language.
	3. Dynamically Typed.
	4. Multi-platform/ portable.
      Disadvantages of Python
	1. Slower Speed than Other Languages.
	2. Not Memory Efficient.
	3. Python’s database access layer.
	4. Runtime Errors.

Q4.->	1. Web development.
	2. Data science.
	3. OS development.
	4. Scientific programming.
	5. Game Development.

Q5.-> A variable is a reserved memory location to store values.we can declare a variable a as a=100 in python.

Q6.-> To take input in python we use the built-in input() function.

Q7.-> By default the input value is in string datatype.

Q8.-> Converting one datatype into another is known as type casting.

Q9.-> We cannot multiple individual inputs from one input function, however we can use the split() function in python to divide the input from same line into multiple values.

Q10.-> Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11.-> No, keywords are special words that have specific purposes and can't be used as variables as they will be recognized by a keyword to execute that specific purpose.

Q12.-> Python indentation refers to adding white space before a statement to a particular block of code. In another word, all the statements with the same space to the right, belong to the same code block.

Q13.-> In python we output using the print statement.

Q14.-> Operators are special symbols that designate that some sort of computation should be performed.

Q15.-> / operater is used o divide and can return decimal values/float values but // operator returns the floor value of number.

Q16.->
		print("iNeuron"*4)

Q17.->

	
	n=float(input("enter number"))

	if n%2==0:
	    print("Even Number",n)
	else:
	    print("Odd number",n)


Q18.-> Boolean Operators are simple words (AND, OR, NOT or AND NOT) used as conjunctions to combine or exclude keywords in a search, resulting in more focused and productive results.

Q19. ->
	1 or 0 = 1
	0 and 0 = 0
	True and False and True = False
	1 or 0 or 0 = 1

Q20.-> Conditional statement is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Q21.-> if, elif, else are keywords used for conditional statements and execute their code when the condition is satisfied.

Q22. ->
	age = int(input("Enter your age: "))
if age>=18:
    print("I can vote")
elif age <18:
    print("I can't vote")
print("Thank You")

Q23. ->

numbers = [12,75,150,180,145,525,50]
evenSum =0
for i in numbers:
    if i%2==0:
        evenSum+=i
    else:
        continue
print("The sum of all even numbers in list is",evenSum)

Q24.->

a = int(input("Enter First Number"))
b = int(input("Enter Two Number"))
c = int(input("Enter Third Number"))

if a>=b:
    if a>c:
        print("Greatest no is",a)
    else:
        print("Greatest no is",c)
else:
    if b>c:
        print("Greatest no is",b)
    else:
        print("Greatest no is",c)

Q25.->
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i%5==0:
        if i>500:
            break
        elif i>150:
            continue
        else:
            print(i,end=" ")

Q26. In Python, Strings are arrays of bytes representing Unicode characters.

Q27. Sqaure brackets can used to access the elements of the string.

Q28.
	print(string[9:16])

Q29. 
	print(string[15:8:-1])

Q30. 
	print(string[::-1])

Q31.
str1 = "Hello"
del(str1)

Q32. The "backslash (\)" character as an escape character. In other words, it has a special meaning when we use it inside the strings. As the name suggests, the escape character escapes the characters in a string for a brief moment to introduce unique inclusion.

Q33. print('iNeuron\'s Big Data Course')

Q34. Python list are dynamically sized array, declared in languages like C++ and Java. A list is a collection of things, enclosed in [ ] and separated by commas. 

Q35.  You can create a list by opening and closing the square brackets [].

Q36. We can access the elements in a list by indexing.

Q37. 
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])


Q38.
n = input("Enter number of elements seprated by space: ").split(" ")
print(len(n))

Q39. 
lst = ["Welcome", "to", "Data", "course"]
lst.insert(2, "Big")

Q40. Tuple is a collection of Python objects much like a list. The sequence of values stored in a tuple can be of any type, and they are indexed by integers. 
Tuples are immutable where as list are mutable. We can also faster through the tuples than the list.

Q41.We can create tuple using round brackets ().

Q42. No, I can't as tuples are immutable. The work around is it typecast tuple to list and then append.

tup = ()
tup = list(tup)
tup.append("Vishal")
tup = tuple(tup)
tup

Q43. Yes, we can.

tup1 = ("Vishal ")
tup2 = ("Singh")
tup1+tup2

Q44. 
x = input("Enter the values separeted by space: ").split(" ")
x = tuple(x)
print(len(x))

Q45. A set is an unordered collection of data types that is iterable, mutable and has no duplicate elements. The order of elements in a set is undefined though it may consist of various elements.

Q46. We can create set using curly brackets {}. Keep in mind empty {} will result in dictionary hence there must be some value in the brackets.

Q47. 
set1 = {"iNeuron"}
set1

Q48. 
set1.add("Big")
set1.add("Data")
set1


Q49. We can add more than one element in a single go using update(), but using add() it's not possible.

Q50. To remove all the elements from the set, clear() function is used.

Q51. Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation. 

Q52. 
- Frozen sets are immutable where as sets are mutable.
- Sets can't be used as keys in dictionary where as frozen sets can be used.

Q53.  Python set Union() Method returns a new set which contains all the items from the original set.

set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {7, 8, 9, 10}
print("set1 U set2 : ", set1 | set2)
print("set1 U set2 U set3 :", set1 |set2 | set3)

Q54. Python set intersection() method returns a new set with an element that is common to all set

set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {4, 6, 8}

print("set1 intersection set2 : ", set1.intersection(set2))

print("set1 intersection set2 intersection set3 :", set1.intersection(set2, set3))


Q55. Dictionary in Python is a collection of keys values, used to store data values like a map, which, unlike other data types which hold only a single value as an element.

Q56. Dictionary is having key and value pair where as all other data structures have only values in them.

Q57. We can create dictionary using curly brackets {}.

Q58. type = dict

Q59. 
Dict = {}
Dict[0] = "Hello"
Dict[1] = "Course: ["Data Science", "Big Data"]"


Q60.
Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
for i, j in Dict.items():
  print(f"Key is {i} and value is {j}")


Q61. 
Dict = {"Name": {"f_name":"Vishal", "l_name":"Singh"}, "Experience": 3, "Organisation":"iNeuron"}
for i, j in Dict["Name"].items():
  print(f"Key is {i} and value is {j}")

Q62. get() is also to access the elements in dictionary.

Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.get("Name"))

Q63. items() method is used to return the list with all dictionary keys with values.

Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.items())

Q64. 
Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.pop("Name"))

Q65. popitem() method removes the last inserted key-value pair from the dictionary and returns it as a tuple.

Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.popitem())

Q66. keys() method returns a view object that displays a list of all the keys in the dictionary.

Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.keys())

Q67. values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary, as a list.

Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.values())

Q68.Loops are used the iterate over a block of statement multiple times.

Q69.There is for and while loop in Python

Q70. When we know the exact number of iterations, we can use for loop. When we want the to run till a certain condition is true we can use while loop.

Q71. Continue Statement skips the execution of the program block from after the continue statement and forces the control to start the next iteration.

Q72. break statement in Python is used to bring the control out of the loop when some external condition is triggered. break statement is put inside the loop body

Q73. The pass statement is a null statement. But the difference between pass and comment is that comment is ignored by the interpreter whereas pass is not ignored. 

Q74. range() function returns a sequence of numbers, in a given range. The most common use of it is to iterate sequence on a sequence of numbers

Q75. 
statesAndCapitals = {
	'Gujarat': 'Gandhinagar',
	'Maharashtra': 'Mumbai',
	'Rajasthan': 'Jaipur',
	'Bihar': 'Patna'
}

for state in statesAndCapitals:
	print(state)

Q76. 
def factorial(n):
  if n < 0:
    return 0
  elif n == 0 or n == 1:
    return 1
  else:
    fact = 1
    while(n>1):
      fact *= n
      n -= 1
    return fact

n=6
print(f"Factorial of {n} is {factorial(n)}")

Q77. 
def SI(p,r,t):
  si = (p*r*t)/100
  print(f"Simple interest is {si}")
  return si

SI(8, 8, 6)

Q78. 
def CI(p, r, t):
  amount = p*(1+r/100)**t
  ci = amount - p
  print(f"Compound intrest is {ci}")
  return ci

CI(10000, 10.25, 5)

Q79.
from math import sqrt

def is_prime(n):
  prime_flag = 0

  if(n > 1):
    for i in range(2, int(sqrt(n)) + 1):
      if (n % i == 0):
        prime_flag = 1
        break
    if (prime_flag == 0):
      print(f"{n} is a prime number.")
    else:
      print(f"{n} is not a prime number.")
  else:
    print(f"{n} is not a prime number.")

is_prime(134)

Q80.
def check_armstrong(n):
  s = n
  b = len(str(n))
  sum1 = 0
  while n != 0:
      r = n % 10
      sum1 = sum1+(r**b)
      n = n//10
  if s == sum1:
      print(f"The given number {s} is armstrong number")
  else:
      print(f"The given number {s} is not armstrong number")

check_armstrong(153)

Q81.
def Fibonacci(n):
	if n<= 0:
		print("Incorrect input")
	elif n == 1:
		return 0
	elif n == 2:
		return 1
	else:
		return Fibonacci(n-1)+Fibonacci(n-2)

print(Fibonacci(7))

Q82.
def swap_list(newList):
	size = len(newList)
	temp = newList[0]
	newList[0] = newList[size - 1]
	newList[size - 1] = temp
	
	return newList

newList = [15, 12, 35, 17, 9, 56, 29]

print(swap_list(newList))

def swap_list(newList):
     
    newList[0], newList[-1] = newList[-1], newList[0]
 
    return newList
     
newList = [15, 12, 35, 17, 9, 56, 29]
print(swap_list(newList))

Q83.
def swapPositions(list, pos1, pos2):
	
	list[pos1], list[pos2] = list[pos2], list[pos1]
	return list

List = [15, 12, 35, 17, 9, 56, 29]
pos1, pos2 = 1, 3

print(f"Original list: {List}")
print(f"Swapped list: {swapPositions(List, pos1, pos2)}")

Q84.
def n_max_elements(list1, N):
	final_list = []

	for i in range(0, N):
		max1 = 0
		
		for j in range(len(list1)):	
			if list1[j] > max1:
				max1 = list1[j];
				
		list1.remove(max1);
		final_list.append(max1)
		
	print(final_list)

list1 = [2, 6, 41, 85, 0, 3, 7, 6, 10]
N = 3

n_max_elements(list1, N)

Q85.
def cumulative_sum(lists):
	cu_list = []
	length = len(lists)
	cu_list = [sum(lists[0:x:1]) for x in range(0, length+1)]
	return cu_list[1:]

lists = [10, 20, 30, 40, 50]
print(f"Cumulative sum of the list is {cumulative_sum(lists)}")

Q86.
def isPalindrome(s):
  if s == s[::-1]:
	  return f"{s} is palindrome"
  return f"{s} is not palindrome"

s = "dad"
isPalindrome(s)

Q87.
def remove_ith_element(i):
  str1 = "Big Data Bootcamp"
  str2 = ""

  for n in range(len(str1)):
    if n == i:
      continue
    else:
      str2 = str2 + str1[n]

  return str2

remove_ith_element(5)

Q88.
def check_substring(s2, s1):
	if (s2.count(s1) > 0):
		print(f'"{s1}" is a substring of "{s2}"')
	else:
		print(f'"{s1}" is not a substring of "{s2}"')


s2 = "Welcome to iNeuron Big Data Bootcamp"
s1 = "iNeuron"
check_substring(s2, s1)

Q89.
def string_greater_than_k(k, str):
	
	string = []

	text = str.split(" ")

	for x in text:

		if len(x) > k:

			string.append(x)

	return string

k = 3
str ="Big Data Bootcamp"
print(string_greater_than_k(k, str))

Q90. 
test_dict = {'iNeuron': [5, 6, 7, 8],
			'is': [10, 11, 7, 5],
			'best': [6, 12, 10, 8],
			'for': [1, 2, 5],
      'big data': [2, 7, 12, 9]
      }

print("The original dictionary is : " + str(test_dict))

res = list(sorted({ele for val in test_dict.values() for ele in val}))

print("The unique values list is : " + str(res))

Q91. 
def Merge(dict1, dict2):
	return(dict2.update(dict1))

dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}

print(Merge(dict1, dict2))

print(dict2)

Q92. 
print (dict([('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]))

Q93.
list1 = [9, 5, 6]

res = [(val, pow(val, 3)) for val in list1]

print(res)

Q94. 
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

res = [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res + [(a, b) for a in test_tuple2 for b in test_tuple1]

print("The filtered tuple : ", str(res))

Q95. 
def Sort_Tuple(tup):
     
    lst = len(tup)
    for i in range(0, lst):
         
        for j in range(0, lst-i-1):
            if (tup[j][1] > tup[j + 1][1]):
                temp = tup[j]
                tup[j]= tup[j + 1]
                tup[j + 1]= temp
    return tup
 
tup =[('452', 10), ('256', 5), ('100', 20), ('135', 15)]
       
print(Sort_Tuple(tup))

Q96. 
def pypart(n):
	
	for i in range(0, n):
	
		for j in range(0, i+1):
		
			print("* ",end="")
	
		print("\r")

n = 5
pypart(n)


Q97. 
def inverse_pattern():
  n=5;i=0
  while(i<=n):
    print(" " * (n - i) +"*" * i)
    i+=1

inverse_pattern()

Q98. 
def triangle(n):
	
	k = n - 1

	for i in range(0, n):

		for j in range(0, k):
			print(end=" ")
	
		k = k - 1
	
		for j in range(0, i+1):

			print("* ", end="")
	
		print("\r")

n = 5
triangle(n)

Q99. 
def numpat(n):

	num = 1

	for i in range(0, n):

		num = 1

		for j in range(0, i+1):

			print(num, end=" ")

			num = num + 1

		print("\r")

n = 5
numpat(n)


Q100. 
def alphapat(n):

	num = 65

	for i in range(0, n):
	
		for j in range(0, i+1):

			ch = chr(num)
		
			print(ch, end=" ")
	
		num = num + 1
	
		print("\r")

n = 5
alphapat(n)