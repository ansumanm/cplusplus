
# Table of Contents
1. [C++ Standards](#c++-standards)
2. [C++ Strings](#c++-string)
   
#  C++ standards

| Standard | Compiler Option | Key Features Introduced                                            |
|----------|-----------------|---------------------------------------------------------------------|
| C++98    | `-std=c++98`    | Initial Standard, Standard Template Library (STL)                   |
| C++03    | `-std=c++03`    | Minor bug fixes and improvements                                    |
| C++11    | `-std=c++11`    | Auto, lambda expressions, nullptr, uniform initialization, range-based for loops |
| C++14    | `-std=c++14`    | Binary literals, digit separators, generic lambdas                  |
| C++17    | `-std=c++17`    | Structured bindings, inline variables, filesystem library           |
| C++20    | `-std=c++20`    | Concepts, coroutines, modules, ranges, spaceship operator (<=>)     |
| C++23    | `-std=c++2b`    | (Partial support, features evolving) Improvements to templates, ranges |

Example to use a standard:
```bash
g++ -std=c++17 main.cpp -o main
```

# C++ string

The C++ `std::string` class, part of the C++ Standard Library, provides a wide range of operations to manipulate strings. Here's a summary of the most common string operations available in C++:

### Construction and Assignment
- **Default constructor**: Initializes an empty string.
- **Copy constructor**: Initializes a string with a copy of another string.
- **Substring constructor**: Initializes a string with a substring of another string.
- **From C-string**: Initializes a string with a C-string.
- **Fill constructor**: Initializes a string with multiple copies of a character.
- **Assignment operator**: Assigns a new value to the string, replacing its current contents.

### Element Access
- **`operator[]`**: Accesses a character at a specified position.
- **`at()`**: Accesses a character at a specified position with bounds checking.
- **`front()`**: Accesses the first character.
- **`back()`**: Accesses the last character.
- **`data()`**: Returns a pointer to the first character.
- **`c_str()`**: Returns a C-string equivalent.

### Capacity
- **`size()`/`length()`**: Returns the number of characters.
- **`max_size()`**: Returns the maximum number of characters the string can hold.
- **`resize()`**: Changes the size of the string.
- **`capacity()`**: Returns the size of the allocated storage.
- **`empty()`**: Checks if the string is empty.
- **`reserve()`**: Requests a change in capacity.
- **`shrink_to_fit()`**: Requests the removal of unused capacity.

### Modifiers
- **`clear()`**: Clears the contents.
- **`insert()`**: Inserts additional characters.
- **`erase()`**: Erases characters.
- **`push_back()`**: Adds a character to the end.
- **`pop_back()`**: Removes the last character.
- **`append()`**: Appends characters to the end.
- **`replace()`**: Replaces part of the string.
- **`swap()`**: Swaps the contents with another string.

### String Operations
- **`substr()`**: Returns a substring.
- **`copy()`**: Copies characters to a C-string.
- **`find()`**: Finds a substring or character.
- **`rfind()`**: Finds a substring or character, searching backwards.
- **`find_first_of()`**: Finds the first character equal to one of the characters in the argument.
- **`find_last_of()`**: Finds the last character equal to one of the characters in the argument.
- **`find_first_not_of()`**: Finds the first character not equal to any of the characters in the argument.
- **`find_last_not_of()`**: Finds the last character not equal to any of the characters in the argument.

### Comparison
- **`compare()`**: Compares the string with another string, substring, or C-string.

### Numeric Conversions
- **`stoi()`, `stol()`, `stoul()`, etc.**: Converts a string to an integer or floating-point number (functions are part of the `<string>` header but not members of `std::string`).

### Concatenation
- **`operator+`**: Concatenates two strings or a string with a character.

These operations provide a comprehensive toolset for string manipulation in C++, allowing for complex and varied string processing tasks.
