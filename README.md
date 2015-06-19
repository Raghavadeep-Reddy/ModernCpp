# ModernCpp
Modern C++ Description

## Examples

### Moving to Modern C++
nullptr.cpp - Compare using "nullptr" in C++11 and using NULL in C++98

scopedEnum.cpp - Compare scoped enum in C++11 and unscoped enum in C++98/C++11

### Classes
defaultKeyword.cpp - Describe "default" keyword by comparing the drawback of the rule of zero

deleteKeyword.cpp - Compare using "delete" keyword in C++11 and declaring special functions (i.e. copy constructor) with private access modifier in C++98

ruleOfFive.cpp - Compare the rule of five in C++11 and the rule of three in C++98

ruleOfZero.cpp - Describe the rule of zero in C++98

### Concurrency
promise.cpp - Describe std::promise and its instructions

## Slides
1st Study - http://www.slideshare.net/utilforever/c-programming-1s-study

2nd Study - http://www.slideshare.net/utilforever/c-programming-2nd-study

3rd Study - http://www.slideshare.net/utilforever/c-programming-3rd-study

4th Study - http://www.slideshare.net/utilforever/c-programming-4th-study

5th Study - http://www.slideshare.net/utilforever/c-programming-5th-study

6th Study - http://www.slideshare.net/utilforever/c-programming-6th-study

7th Study - http://www.slideshare.net/utilforever/c-programming-7th-study

8th Study - http://www.slideshare.net/utilforever/c-programming-8th-study

## Curriculum
1. From C To C++
  - (1st) printf, scanf -> std::cin, std::cout
  - (1st) bool type
  - (1st) auto
  - (2nd) Range-based for
  - (2nd) malloc, free -> new, delete
  - (2nd) NULL -> nullptr
  - (2nd) Casting 1: static_cast 
  - (3rd) Scoped enum
  - (3rd) Binary literal, Separator
  - (3rd) std::string 
  - (4th) Reference
  - (4th) Function overloading
  - (4th) Namespace
  - (TBD) decltype
  - (TBD) Casting 2: dynamic_cast, const_cast, reinterpret_cast
  - (TBD) typedef -> type alias
  - (TBD) Uniform initialization
  - (TBD) Initializer list
  - (TBD) Lambda expression
  - (TBD) Lvalue / Rvalue reference
  - (TBD) Move semantics
  - (TBD) Perfect forwarding
  - (TBD) Smart pointer: unique_ptr, shared_ptr, weak_ptr
2. OOP: Object-Oriented Programming
  - (5th) Class and Object
  - (5th) Access modifier: public, protected, private
  - (5th) Information hiding, Encapsulation
  - (6th) Constructor
  - (6th) Destructor
  - (6th) this pointer
  - (7th) Copy constructor
  - (7th) Copy assignment operator
  - (7th) Shallow copy, Deep copy
  - (7th) Rule of zero, Rule of three
  - (8th) Member variable: static / const / reference / const reference
  - (8th) Method: static / const / method overloading / default parameter / inline
  - (9th) Inheritance
  - (9th) Up / Down casting
  - (10th) Overriding: virtual keyword 
  - (10th) Polymorphism
  - (10th) Pure virtual method
  - (11th) Operator overloading
  - (12th) Multiple inheritance
  - (12th) vtable, RTTI
  - (TBD) Special functions 3: Move constructor, Move assignment operator
  - (TBD) Special functions 4: std::initializer_list constructor, Inheriting constructor
  - (TBD) Rule of five
  - (TBD) =default, =delete 
  - (TBD) explicit keyword
  - (TBD) friend 
  - (TBD) mutable
  - (TBD) overriding keyword
  - (TBD) final keyword
  - (TBD) PIMPL
3. Exception Handling
  - (13th) Basic: try, catch, throw
  - (TBD) throw list
  - (TBD) noexcept
  - (TBD) Exception and polymorphism
  - (TBD) Nested exception
  - (TBD) Stack unwinding
  - (TBD) Function-try-block
4. Generic Programming: Template
  - (14th) Template parameter
  - (14th) Template method
  - (14th) Template class
  - (TBD) Template specialization
  - (TBD) Partial specialization
  - (TBD) Template inheritance vs template specialization
  - (TBD) Template aliases
  - (TBD) decltype + auto
  - (TBD) Function template
  - (TBD) Template recursion
  - (TBD) Variadic template
  - (TBD) Variable template
  - (TBD) Type inference
  - (TBD) SFINAE
  - (TBD) Template metaprogramming
  - (TBD) Type traits
  - (TBD) constexpr
5. Concurrency: Multithreading Programming
  - (TBD) Race condition, Deadlock
  - (TBD) Atomic task
  - (TBD) thread
  - (TBD) mutex, lock, call_once
  - (TBD) condition_variable
  - (TBD) async
  - (TBD) future, promise
  - (TBD) Thread pool
6. STL: Standard Library
  - (15th) vector, deque, list, array
  - (16th) queue, priority_queue, stack
  - (17th) pair, tuple, map, multimap, set, multiset
  - (18th) algorithm
  - (TBD) function
  - (TBD) forward_list
  - (TBD) unordered_map, unordered_multimap, unordered_set, unordered_multiset
  - (TBD) bitset
  - (TBD) ratio
  - (TBD) chrono
  - (TBD) random
  - (TBD) regular expression