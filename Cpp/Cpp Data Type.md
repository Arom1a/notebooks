## 1 Basic types
1. Integers
    `int`
2. Floating points
    `float`
    `double`
3. Characters
    `char`
4. Booleans
    `bool`
5. Strings
    `string`

Modifiers:
1. signed
    `int` is signed by default. 
    `signed` and `unsigned` can be only used with `int` and `char`. 
2. unsigned
    `signed` and `unsigned` can be only used with `int` and `char`. 
3. short
    `short int` can be also write as `short`. 
4. long
    `long int` can be also write as `long`. 

## 2 Derived types
1. Functions
	`FunctionType FunctionName(parameters){};`
2. Arrays
	`DataType ArrayName[size_of_array];`
3. Pointers
	`dataType *ptrName = {&varName};`
	`&varName` means the address of the `var`. 
	To access or change the value of the var, we can use `*ptrName`. 
	```cpp
	// This script initializes a variable and creates a pointer toward the variable. It also demonstrates pointers can be used to change the value. 
	 int main()
	{
	    int myScore {98};
	    int *ptrScore {&myScore};
	    cout << "My score is " << myScore << '\n';
	    cout << ptrScore << '\n';
	    cout << *ptrScore << '\n';
	    *ptrScore = 100;
	    cout << "Now my score is " << myScore << ", yeah! \n";
	}
	```
4. References
	`dataType &newName = varName`