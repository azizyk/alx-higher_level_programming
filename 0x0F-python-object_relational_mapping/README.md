# 0x0F. Python - Object-relational mapping
# Tasks
- 0. Get all states
	+ 0-select_states.py: Python script that uses MySQLdb to list all states in the database hbtn_0e_0_usa.
	+ Usage: ./0-select_states.py <mysql username> <mysql password> <database name>.
	+ Results are ordered by ascending states.id.
- 1. Filter states

	+ 1-filter_states.py: Python script that uses MySQLdb to list all states with names starting with N in the database hbtn_0e_0_usa.
	+ Usage: ./1-filter_states.py <mysql username> <mysql password> <database name>.
	+ Results are ordered by ascending states.id.
- 2. Filter states by user input
	+ 2-my_filter_states.py: Python script that uses MySQLdb to display all values matching a given name in the states table of the database hbtn_0e_0_usa.
	+ Usage: ./2-my_filter_states.py <mysql username> <mysql password> <database name> <state name searched>.
	+ Results are ordered by ascending states.id.
	+ Uses string formatting to construct the SQL query.
- 3. SQL Injection...
	+ 3-my_safe_filter_states.py: Python script that uses MySQLdb to display all values matching a given name in the states table of the database hbtn_0e_0_usa.
	+ Usage: ./3-my_safe_filter_states.py <mysql username> <mysql password> <database name> <state name searched>.
	+ Results are ordered by ascending states.id.
	+ Safe from SQL injections.
