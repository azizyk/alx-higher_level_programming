# 0x05-python-exceptions
## About 
- Exceptions and how to use them
- Handle an exception
- Catching exceptions 
- Raise a builtin exception 
- Clean-up actions 
# Requirements
- Compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- Code should use the pycodestyle (version 2.8.*)
# file descriptions
**Mamdatory**
- 0-square_matrix_simple.py - Write a function that computes the square value of all integers of a matrix.
	+ Prototype: def square_matrix_simple(matrix=[]):
	+ matrix is a 2 dimensional array
	 + Returns a new matrix:
	      Same size as matrix Each value should be the square of the value of the input

	+ Initial matrix should not be modified
	+ You are not allowed to import any module
	+ You are allow to use regular loops, map, etc.
- 1-safe_print_integer.py - function that prints an integer with "{:d}".format().
- 2-safe_print_list_integers.py:- Write a function that prints the first x elements of a list and only integers.
- 3-safe_print_division.py - function that divides two integers and prints the result.

- 4-list_division.py - function that divides two lists element by element.
- 5-raise_exception.py - function that raises a type exception.
-6-raise_exception_msg.py - function that raises a name exception with a message.

**Advanced**

- 100-safe_print_integer_err.py - function that prints an integer or the exception that was raised.
- 101-safe_function.py - function that executes a function safely.
- 102-magic_calculation.py - function that does exactly the same as the following Python bytecode:

  3           0 LOAD_CONST               1 (0)
              3 STORE_FAST               2 (result)

  4           6 SETUP_LOOP              94 (to 103)
              9 LOAD_GLOBAL              0 (range)
             12 LOAD_CONST               2 (1)
             15 LOAD_CONST               3 (3)
             18 CALL_FUNCTION            2 (2 positional, 0 keyword pair)
             21 GET_ITER
        >>   22 FOR_ITER                77 (to 102)
             25 STORE_FAST               3 (i)

  5          28 SETUP_EXCEPT            49 (to 80)

  6          31 LOAD_FAST                3 (i)
             34 LOAD_FAST                0 (a)
             37 COMPARE_OP               4 (>)
             40 POP_JUMP_IF_FALSE       58

  7          43 LOAD_GLOBAL              1 (Exception)
             46 LOAD_CONST               4 ('Too far')
             49 CALL_FUNCTION            1 (1 positional, 0 keyword pair)
             52 RAISE_VARARGS            1
             55 JUMP_FORWARD            18 (to 76)

  9     >>   58 LOAD_FAST                2 (result)
             61 LOAD_FAST                0 (a)
             64 LOAD_FAST                1 (b)
             67 BINARY_POWER
             68 LOAD_FAST                3 (i)
             71 BINARY_TRUE_DIVIDE
             72 INPLACE_ADD
             73 STORE_FAST               2 (result)
        >>   76 POP_BLOCK
             77 JUMP_ABSOLUTE           22

 10     >>   80 POP_TOP
             81 POP_TOP
             82 POP_TOP

 11          83 LOAD_FAST                1 (b)
             86 LOAD_FAST                0 (a)
             89 BINARY_ADD
             90 STORE_FAST               2 (result)

 12          93 BREAK_LOOP
             94 POP_EXCEPT
             95 JUMP_ABSOLUTE           22
             98 END_FINALLY
             99 JUMP_ABSOLUTE           22
        >>  102 POP_BLOCK

 13     >>  103 LOAD_FAST                2 (result)
            106 RETURN_VALUE

