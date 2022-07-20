# 0x06. Python - Classes and Objects
## About 
- Object Oriented Programming
- Python Class
- What is an object and an instance 
- Difference between a class and an object or instance
- Using a public, Protected and Private attribute 
- Using the special __init__ methode
- Data abstract, Data Encapsulation, and information Hiding
- Difference between an attribute and a property in python
- Binding attributes to object and classes

## Requirements
- Compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- Code should use the pycodestyle (version 2.8.*)
## File Description
**Mandatory**
- 0-square.py: Python class Square that defines a square.
- 1-square.py: Python class Square that defines a square. Builds on 0-square.py with:
	+ Private instance attribute size.
	+ Instantiation with size.
- 2-square.py: Write a class Square that defines a square by: (based on 1-square.py)
	+ Private instance attribute: size
	+ Instantiation with optional size: def __init__(self, size=0):
		- size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
		- if size is less than 0, raise a ValueError exception with the message size must be >= 0
3-square.py: Write a class Square that defines a square by: (based on 2-square.py)
- Private instance attribute: size
- Instantiation with optional size: def __init__(self, size=0):
	+ size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
	+ if size is less than 0, raise a ValueError exception with the message size must be >= 0
- Public instance method: def area(self): that returns the current square area
4-square.py: Write a class Square that defines a square by: (based on 3-square.py)

- Private instance attribute: size:
	+ property def size(self): to retrieve it
	+ property setter def size(self, value): to set it:
		- size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
		- if size is less than 0, raise a ValueError exception with the message size must be >= 0
- Instantiation with optional size: def __init__(self, size=0):
- Public instance method: def area(self): that returns the current square area
5-square.py: Write a class Square that defines a square by: (based on 4-square.py)

- Private instance attribute: size:
	+ property def size(self): to retrieve it
	+ property setter def size(self, value): to set it:
		- size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
		- if size is less than 0, raise a ValueError exception with the message size must be >= 0
- Instantiation with optional size: def __init__(self, size=0):
- Public instance method: def area(self): that returns the current square area
- Public instance method: def my_print(self): that prints in stdout the square with the character #:
	+ if size is equal to 0, print an empty line
6-square.py: Python class Square that defines a square. Builds on 5-square.py with:
	+ Private instance attribute position.
	+ Property def position(self): to retreive position.
	+ Property setter def position(self, value): to set position.
	+ Instantiation with optional size and position: def __init__(self, size=0, position=(0, 0)):
- If a provided position attribute is not a tuple of two integers, a TypeError exception is raised with the message position must be a tuple of 2 positive integers.

**Advanced**
- 100-singly_linked_list.py: Python classes Node and SinglyLinkedList that define a node of a singly-linked list and a singly-linked list. The class Node is defined with:
	+ Private instance attribute data.
	+ Property def data(self): to set data.
	+ Property setter def data(self, value): to set data.
	+ Private instance attribute next_node.
	+ Property def next_node(self): to set next_node.
	+ Property def next_node(self, value): to set next_node.
	+ Instantiation with data and next_node: def __init__(self, data, next_node=None):
- If a provided data attribute is not an integer, a TypeError exception is raised with the message data must be an integer.
- If a provided next_node attribute is not a Node or None, a TypeError exception is raised with the message next_node must be a Node object.
- The class SinglyLinkedList is defined with:
	+ Private instance attribute head.
	+ Instantiation def __init__(self):
	+ Public instance method def sorted_insert(self, value): that inserts a new Node into the correct sorted position in the list increasing order).
- 101-square.py: Python class Square that defines a square. Builds on 6-square.py with:
	+ Method __str__ to set printing of a Square instance equivalent to my_print().
- 102-square.py: Python class Square that defines a square. Builds on 101-square.py with:
	+ Methods __eq__, __ne__, __lt__, __le__, __gt__, and __ge__, to enable usage of Square instances with logical operators ==, !=, <, <=, >, and >=, respectively, based on the square area.

- 103-magic_class.py: Python function matching exactly a bytecode provided by Holberton School.
