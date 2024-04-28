[Containers in C++ STL (Standard Template Library) - GeeksforGeeks](https://www.geeksforgeeks.org/containers-cpp-stl)
## 1 Sequence Containers
### 1.1 `array`
Include this in the Header: `#include <array>`
Create and initializing an array: `array<dataType, numberOfValues> name{};`

### 1.2 `vector`
Include this in the header: `#include <vector>`
Create and initializing a vector: `vector<dataType> name {};`
Ways to initialize vectors: 
```cpp
// empty initialize
vector<dataType> name(numberOfElements);
vector<dataType> name(numberOfElements, valueOfElement);

// initialize with values
vector<dataType> name{value1, value2, value3 ...};

// copy another vector
vector<dataType> name(anotherVector);
vector<dataType> name(anotherVector.begin(), anotherVector.begin() + n);
```

### 1.3 `deque`

### 1.4 `forward-list`

## 2 Associative Containers



## 3 Unordered Associative Containers



## 4 Container Adapters
### 4.1 Stack
A stack is a LIFO (last in first out)

Include this in the header: `#include <stack>`
`deque` is the default container for `stack`. 
**Initializing using `deque`:** 
```cpp
stack<dataType> myStack (myDeque);
```
**Initializing using `vector`:** 
```cpp
stack<dataType, vector<dataType>> myStack (myVector);
```
**Initializing using `list`:** 
```cpp
stack<dataType, list<dataType>> myStack (myList);
```
Stacks do not have iterators. 

### 4.2 Queue
A queue is a FILO (first in last out)
Include this in the header: `#include <queue>`