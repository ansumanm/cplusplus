
# Table of Contents
1. [C++ Standards](#c++-standards)
   
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
