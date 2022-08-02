# 0x0B. Python - Input/Output
## About 
- Opning a file
- Writing text in a file
- Reading the full content of a file
- Reading a file line by line
- Converting a python data stracture to a JSON string
- Convert a JSON string to a python data structure
## Requirements
- Compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- Code should use the pycodestyle (version 2.8.*)
## File description
**Mandatory tasks**
- 0-Write a function that reads a text file (UTF8) and prints it to stdout:
- 1-Write a function that writes a string to a text file (UTF8) and returns the number of characters written:
- 2- Write a function that appends a string at the end of a text file (UTF8) and returns the number of characters added:
- 3-Write a function that returns the JSON representation of an object (string):
- 4-Write a function that returns an object (Python data structure) represented by a JSON string:
- 5-Write a function that writes an Object to a text file, using a JSON representation:
- 6-Write a function that creates an Object from a “JSON file”:
- 7-Write a script that adds all arguments to a Python list, and then save them to a file:
- 8-Write a function that returns the dictionary description with simple data structure (list, dictionary, string, integer and boolean) for JSON serialization of an object:
- 9-Write a class Student that defines a student by:
	+ Public instance attributes first_name, last_name, and age.
	+ Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):.
	+ Public method def to_json(self): that returns the dictionary representation of a Student instance (same as 8-class_to_json.py)
- 10-Write a class Student that defines a student by:
	+ Public instance attributes first_name, last_name, and age.
	+ Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):.
	+ Public method def to_json(self): that returns the dictionary representation of a Student instance (same as 8-class_to_json.py)
	- If attrs is a list of strings, only attribute names contained in this list must be retrieved.
	- Otherwise, all attributes must be retrieved
- 11-Write a class Student that defines a student by: (based on 10-student.py)
	+ Public instance attributes: first_name, last_name, and age.
	+ Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):
	+ Public method def to_json(self): that returns the dictionary representation of a Student instance (same as 8-class_to_json.py>
		- If attrs is a list of strings, only attributes name contain in this list must be retrieved.
		- Otherwise, all attributes must be retrieved
	+ Public method def reload_from_json(self, json): that replaces all attributes of the Student instance:
		- You can assume json will always be a dictionary
		- A dictionary key will be the public attribute name
		- A dictionary value will be the value of the public attribute
- 12-pascal_triangle.py: Create a def pascal_trinangle(n): that returns a list of lists of integers representing Pascal's triangle of size n.
Assumes the size parameter n is an integer.
	+ If n is less than or equal to 0, returns an empty list.

**Advanced tasks**

- 100-append_after.py: Write a function that inserts a line of text to a file after each line containing a specified string.
- 101-stats.py: Write a script that reads stdin line by line and computes metrics:
	+ Total file size up that point: File size: <total size>
	+ Status code of each read line, printed in ascending order: <status code>: <number>
	+ Input format: <IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size>
