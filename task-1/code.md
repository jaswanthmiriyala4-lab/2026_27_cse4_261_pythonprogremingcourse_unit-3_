Step 1: Create an empty list


python
my_list = []
Here, we create an empty list named my_list.


represents an empty list in Python.
We will store elements in this list.

Step 2: Get the number of elements


python
n = int(input("Enter the number of elements: "))
input() is used to get input from the user.

int() converts the input into an integer.

The value is stored in the variable n.

For example, if you enter 5, the program will accept 5 elements.

Step 3: Create the list using a for loop


python
for i in range(n):
The for loop is used to repeat a set of statements.

range(n) repeats the loop n times.

If n = 5, the loop runs 5 times.

Step 4: Get elements from the user


python
element = input("Enter element: ")
This statement asks the user to enter an element.

The entered value is stored in the variable element.

Step 5: Add elements to the list


python
my_list.append(element)
append() is a built-in Python list method.

It adds the entered element at the end of the list.

For example:

my_list = ['10', '20', '30']

Step 6: Display the heading


python
print("\nElements in the list are:")
print() displays the given message.

\n is used to print the message on a new line.

Step 7: Traverse the list


python
for item in my_list:
This loop visits each element in the list one by one.

Each element is temporarily stored in the variable item.

Step 8: Display the elements


python
print(item)
This statement prints each element of the list.

It displays all elements one by one.

3. Sample Output

text
Enter the number of elements: 5
Enter element: 10
Enter element: 20
Enter element: 30
Enter element: 40
Enter element: 50

Elements in the list are:
10
20
30
40
50
4. Important Functions Used
Function

Purpose

input()

Gets input from the user

int()

Converts input into an integer

range()

Repeats the loop

append()

Adds elements to the list

print()

Displays output

for loop

Traverses the list

5. What is the meaning of Create, Traverse and Display?
Create: Making a list and storing elements in it.

Traverse: Visiting each element of the list one by one.

Display: Printing the elements on the screen.

Exam tip: Remember these three important points:


– Creates an empty list.
append() – Adds elements to the list.

for loop – Traverses and displays the elements.

This is the basic concept of list operations in Python. 😊



