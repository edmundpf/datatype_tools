# Data Type Tools
> Includes useful helper methods for Python's immutable data types using the *forbiddenfruit* library.
## Dict Tools
	* *sort_by_val*
		 * Sorts dictionary by value, expects dictionary with a depth of 1
		   ``` python
		   >>> obj = { 'a': 3, 'b': 1, 'c': 2 }
		   >>> obj.sort_by_val(sort_type='int')
		   {'b': 1, 'c': 2, 'a': 3}
		   ```
