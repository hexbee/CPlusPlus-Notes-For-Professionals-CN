# 目录

* [第1章 快速入门C++](content/chapter1/1.0-Getting-started-with-CPP.md)
    * [1.1 Hello World](content/chapter1/1.1-Hello-World.md)
    * 1.2 Comments
    * 1.3 The standard C++ compilation process
    * 1.4 Function
    * 1.5 Visibility of function prototypes and declarations
    * 1.6 Preprocessor
* 第2章 Literals
    * 2.1 this
    * 2.2 Integer literal
    * 2.3 true
    * 2.4 false
    * 2.5 nullptr
* 第3章 operator precedence
    * 3.1 Logical && and || operators: short-circuit
    * 3.2 Unary Operators
    * 3.3 Arithmetic operators
    * 3.4 Logical AND and OR operators
* 第4章 Floating Point Arithmetic
    * 4.1 Floating Point Numbers are Weird
* 第5章 Bit Operators
    * 5.1 | - bitwise OR
    * 5.2 ^ - bitwise XOR (exclusive OR)
    * 5.3 & - bitwise AND
    * 5.4 << - left shift
    * 5.5 >> - right shift
* 第6章 Bit Manipulation
    * 6.1 Remove rightmost set bit
    * 6.2 Set all bits
    * 6.3 Toggling a bit
    * 6.4 Checking a bit
    * 6.5 Counting bits set
    * 6.6 Check if an integer is a power of 2
    * 6.7 Setting a bit
    * 6.8 Clearing a bit
    * 6.9 Changing the nth bit to x
    * 6.10 Bit Manipulation Application: Small to Capital Letter
* 第7章 Bit fields
    * 7.1 Declaration and Usage
* 第8章 Arrays
    * 8.1 Array initialization
    * 8.2 A fixed size raw array matrix (that is, a 2D raw array)
    * 8.3 Dynamically sized raw array
    * 8.4 Array size: type safe at compile time
    * 8.5 Expanding dynamic size array by using std::vector
    * 8.6 A dynamic size matrix using std::vector for storage
* 第9章 Iterators
    * 9.1 Overview
    * 9.2 Vector Iterator
    * 9.3 Map Iterator
    * 9.4 Reverse Iterators
    * 9.5 Stream Iterators
    * 9.6 C Iterators (Pointers)
    * 9.7 Write your own generator-backed iterator
* 第10章 Basic input/output in c++
    * 10.1 user input and standard output
* 第11章 Loops
    * 11.1 Range-Based For
    * 11.2 For loop
    * 11.3 While loop
    * 11.4 Do-while loop
    * 11.5 Loop Control statements : Break and Continue
    * 11.6 Declaration of variables in conditions
    * 11.7 Range-for over a sub-range
* 第12章 File I/O
    * 12.1 Writing to a file
    * 12.2 Opening a file
    * 12.3 Reading from a file
    * 12.4 Opening modes
    * 12.5 Reading an ASCII file into a std::string
    * 12.6 Writing files with non-standard locale settings
    * 12.7 Checking end of file inside a loop condition, bad practice?
    * 12.8 Flushing a stream
    * 12.9 Reading a file into a container
    * 12.10 Copying a file
    * 12.11 Closing a file
    * 12.12 Reading a `struct` from a formatted text file
* 第13章 C++ Streams
    * 13.1 String streams
    * 13.2 Printing collections with iostream
* 第14章 Stream manipulators
    * 14.1 Stream manipulators
    * 14.2 Output stream manipulators
    * 14.3 Input stream manipulators
* 第15章 Flow Control
    * 15.1 case
    * 15.2 switch
    * 15.3 catch
    * 15.4 throw
    * 15.5 default
    * 15.6 try
    * 15.7 if
    * 15.8 else
    * 15.9 Conditional Structures: if, ifelse
    * 15.10 goto
    * 15.11 Jump statements : break, continue, goto, exit
    * 15.12 return
* 第16章 Metaprogramming
    * 16.1 Calculating Factorials
    * 16.2 Iterating over a parameter pack
    * 16.3 Iterating with std::integer_sequence
    * 16.4 Tag Dispatching
    * 16.5 Detect Whether Expression is Valid
    * 16.6 If-then-else
    * 16.7 Manual distinction of types when given any type T
    * 16.8 Calculating power with C++11 (and higher)
    * 16.9 Generic Min/Max with variable argument count
* 第17章 const keyword
    * 17.1 Avoiding duplication of code in const and non-const getter methods
    * 17.2 Const member functions
    * 17.3 Const local variables
    * 17.4 Const pointers
* 第18章 mutable keyword
    * 18.1 mutable lambdas
    * 18.2 non-static class member modifier
* 第19章 Friend keyword
    * 19.1 Friend function
    * 19.2 Friend method
    * 19.3 Friend class
* 第20章 Type Keywords
    * 20.1 class
    * 20.2 enum
    * 20.3 struct
    * 20.4 union
* 第21章 Basic Type Keywords
    * 21.1 char
    * 21.2 char16_t
    * 21.3 char32_t
    * 21.4 int
    * 21.5 void
    * 21.6 wchar_t
    * 21.7 float
    * 21.8 double
    * 21.9 long
    * 21.10 short
    * 21.11 bool
* 第22章 Variable Declaration Keywords
    * 22.1 decltype
    * 22.2 const
    * 22.3 volatile
    * 22.4 signed
    * 22.5 unsigned
* 第23章 Keywords
    * 23.1 asm
    * 23.2 Dierent keywords
    * 23.3 typename
    * 23.4 explicit
    * 23.5 sizeof
    * 23.6 noexcept
* 第24章 Returning several values from a function
    * 24.1 Using std::tuple
    * 24.2 Structured Bindings
    * 24.3 Using struct
    * 24.4 Using Output Parameters
    * 24.5 Using a Function Object Consumer
    * 24.6 Using std::pair
    * 24.7 Using std::array
    * 24.8 Using Output Iterator
    * 24.9 Using std::vector
* 第25章 Polymorphism
    * 25.1 Define polymorphic classes
    * 25.2 Safe downcasting
    * 25.3 Polymorphism & Destructors
* 第26章 References
    * 26.1 Defining a reference
* 第27章 Value and Reference Semantics
    * 27.1 Definitions
    * 27.2 Deep copying and move support
* 第28章 C++ function "call by value" vs
"call by reference"
    * 28.1 Call by value
* 第29章 Copying vs Assignment
    * 29.1 Assignment Operator
    * 29.2 Copy Constructor
    * 29.3 Copy Constructor Vs Assignment Constructor
* 第30章 Pointers
    * 30.1 Pointer Operations
    * 30.2 Pointer basics
    * 30.3 Pointer Arithmetic
* 第31章 Pointers to members
    * 31.1 Pointers to static member functions
    * 31.2 Pointers to member functions
    * 31.3 Pointers to member variables
    * 31.4 Pointers to static member variables
* 第32章 The This Pointer
    * 32.1 this Pointer
    * 32.2 Using the this Pointer to Access Member Data
    * 32.3 Using the this Pointer to Dierentiate Between Member Data and Parameters
    * 32.4 this Pointer CV-Qualifiers
    * 32.5 this Pointer Ref-Qualifiers
* 第33章 Smart Pointers
    * 33.1 Unique ownership (std::unique_ptr)
    * 33.2 Sharing ownership (std::shared_ptr)
    * 33.3 Sharing with temporary ownership (std::weak_ptr)
    * 33.4 Using custom deleters to create a wrapper to a C interface
    * 33.5 Unique ownership without move semantics (auto_ptr)
    * 33.6 Casting std::shared_ptr pointers
    * 33.7 Writing a smart pointer: value_ptr
    * 33.8 Getting a shared_ptr referring to this
* 第34章 Classes/Structures
    * 34.1 Class basics
    * 34.2 Final classes and structs
    * 34.3 Access specifiers
    * 34.4 Inheritance
    * 34.5 Friendship
    * 34.6 Virtual Inheritance
    * 34.7 Private inheritance: restricting base class interface
    * 34.8 Accessing class members
    * 34.9 Member Types and Aliases
    * 34.10 Nested Classes/Structures
    * 34.11 Unnamed struct/class
    * 34.12 Static class members
    * 34.13 Multiple Inheritance
    * 34.14 Non-static member functions
* 第35章 Function Overloading
    * 35.1 What is Function Overloading?
    * 35.2 Return Type in Function Overloading
    * 35.3 Member Function cv-qualifier Overloading
* 第36章 Operator Overloading
    * 36.1 Arithmetic operators
    * 36.2 Array subscript operator
    * 36.3 Conversion operators
    * 36.4 Complex Numbers Revisited
    * 36.5 Named operators
    * 36.6 Unary operators
    * 36.7 Comparison operators
    * 36.8 Assignment operator
    * 36.9 Function call operator
    * 36.10 Bitwise NOT operator
    * 36.11 Bit shift operators for I/O
* 第37章 Function Template Overloading
    * 37.1 What is a valid function template overloading?
* 第38章 Virtual Member Functions
    * 38.1 Final virtual functions
    * 38.2 Using override with virtual in C++11 and later
    * 38.3 Virtual vs non-virtual member functions
    * 38.4 Behaviour of virtual functions in constructors and destructors
    * 38.5 Pure virtual functions
* 第39章 Inline functions
    * 39.1 Non-member inline function definition
    * 39.2 Member inline functions
    * 39.3 What is function inlining?
    * 39.4 Non-member inline function declaration
* 第40章 Special Member Functions
    * 40.1 Default Constructor
    * 40.2 Destructor
    * 40.3 Copy and swap
    * 40.4 Implicit Move and Copy
* 第41章 Non-Static Member Functions
    * 41.1 Non-static Member Functions
    * 41.2 Encapsulation
    * 41.3 Name Hiding & Importing
    * 41.4 Virtual Member Functions
    * 41.5 Const Correctness
* 第42章 Constant class member functions
    * 42.1 constant member function
* 第43章 C++ Containers
    * 43.1 C++ Containers Flowchart
* 第44章 Namespaces
    * 44.1 What are namespaces?
    * 44.2 Argument Dependent Lookup
    * 44.3 Extending namespaces
    * 44.4 Using directive
    * 44.5 Making namespaces
    * 44.6 Unnamed/anonymous namespaces
    * 44.7 Compact nested namespaces
    * 44.8 Namespace alias
    * 44.9 Inline namespace
    * 44.10 Aliasing a long namespace
    * 44.11 Alias Declaration scope
* 第45章 Header Files
    * 45.1 Basic Example
    * 45.2 Templates in Header Files
* 第46章 Using declaration
    * 46.1 Importing names individually from a namespace
    * 46.2 Redeclaring members from a base class to avoid name hiding
    * 46.3 Inheriting constructors
* 第47章 std::string
    * 47.1 Tokenize
    * 47.2 Conversion to (const) char*
    * 47.3 Using the std::string_view class
    * 47.4 Conversion to std::wstring
    * 47.5 Lexicographical comparison
    * 47.6 Trimming characters at start/end
    * 47.7 String replacement
    * 47.8 Converting to std::string
    * 47.9 Splitting
    * 47.10 Accessing a character
    * 47.11 Checking if a string is a prefix of another
    * 47.12 Looping through each character
    * 47.13 Conversion to integers/floating point types
    * 47.14 Concatenation
    * 47.15 Converting between character encodings
    * 47.16 Finding character(s) in a string
* 第48章 std::array
    * 48.1 Initializing an std::array
    * 48.2 Element access
    * 48.3 Iterating through the Array
    * 48.4 Checking size of the Array
    * 48.5 Changing all array elements at once
* 第49章 std::vector
    * 49.1 Accessing Elements
    * 49.2 Initializing a std::vector
    * 49.3 Deleting Elements
    * 49.4 Iterating Over std::vector
    * 49.5 vector<bool>: The Exception To So Many, So Many Rules
    * 49.6 Inserting Elements
    * 49.7 Using std::vector as a C array
    * 49.8 Finding an Element in std::vector
    * 49.9 Concatenating Vectors
    * 49.10 Matrices Using Vectors
    * 49.11 Using a Sorted Vector for Fast Element Lookup
    * 49.12 Reducing the Capacity of a Vector
    * 49.13 Vector size and capacity
    * 49.14 Iterator/Pointer Invalidation
    * 49.15 Find max and min Element and Respective Index in a Vector
    * 49.16 Converting an array to std::vector
    * 49.17 Functions Returning Large Vectors
* 第50章 std::map
    * 50.1 Accessing elements
    * 50.2 Inserting elements
    * 50.3 Searching in std::map or in std::multimap
    * 50.4 Initializing a std::map or std::multimap
    * 50.5 Checking number of elements
    * 50.6 Types of Maps
    * 50.7 Deleting elements
    * 50.8 Iterating over std::map or std::multimap
    * 50.9 Creating std::map with user-defined types as key
* 第51章 std::optional
    * 51.1 Using optionals to represent the absence of a value
    * 51.2 optional as return value
    * 51.3 value_or
    * 51.4 Introduction
    * 51.5 Using optionals to represent the failure of a function
* 第52章 std::function: To wrap any element that is callable
    * 52.1 Simple usage
    * 52.2 std::function used with std::bind
    * 52.3 Binding std::function to a dierent callable types
    * 52.4 Storing function arguments in std::tuple
    * 52.5 std::function with lambda and std::bind
    * 52.6 `function` overhead
* 第53章 std::forward_list
    * 53.1 Example
    * 53.2 Methods
* 第54章 std::pair
    * 54.1 Compare operators
    * 54.2 Creating a Pair and accessing the elements
* 第55章 std::atomics
    * 55.1 atomic types
* 第56章 std::variant
    * 56.1 Create pseudo-method pointers
    * 56.2 Basic std::variant use
    * 56.3 Constructing a `std::variant`
* 第57章 std::iomanip
    * 57.1 std::setprecision
    * 57.2 std::setfill
    * 57.3 std::setiosflags
    * 57.4 std::setw
* 第58章 std::any
    * 58.1 Basic usage
* 第59章 std::set and std::multiset
    * 59.1 Changing the default sort of a set
    * 59.2 Deleting values from a set
    * 59.3 Inserting values in a set
    * 59.4 Inserting values in a multiset
    * 59.5 Searching values in set and multiset
* 第60章 std::integer_sequence
    * 60.1 Turn a std::tuple<T.> into function parameters
    * 60.2 Create a parameter pack consisting of integers
    * 60.3 Turn a sequence of indices into copies of an element
* 第61章 Using std::unordered_map
    * 61.1 Declaration and Usage
    * 61.2 Some Basic Functions
* 第62章 Standard Library Algorithms
    * 62.1 std::next_permutation
    * 62.2 std::for_each
    * 62.3 std::accumulate
    * 62.4 std::find
    * 62.5 std::min_element
    * 62.6 std::find_if
    * 62.7 Using std::nth_element To Find The Median (Or Other Quantiles)
    * 62.8 std::count
    * 62.9 std::count_if
* 第63章 The ISO C++ Standard
    * 63.1 Current Working Drafts
    * 63.2 C++17
    * 63.3 C++11
    * 63.4 C++14
    * 63.5 C++98
    * 63.6 C++03
    * 63.7 C++20
* 第64章 Inline variables
    * 64.1 Defining a static data member in the class definition
* 第65章 Random number generation
    * 65.1 True random value generator
    * 65.2 Generating a pseudo-random number
    * 65.3 Using the generator for multiple distributions
* 第66章 Date and time using <chrono> header
    * 66.1 Measuring time using <chrono>
    * 66.2 Find number of days between two dates
* 第67章 Sorting
    * 67.1 Sorting and sequence containers
    * 67.2 sorting with std::map (ascending and descending)
    * 67.3 Sorting sequence containers by overloaded less operator
    * 67.4 Sorting sequence containers using compare function
    * 67.5 Sorting sequence containers using lambda expressions (C++11)
    * 67.6 Sorting built-in arrays
    * 67.7 Sorting sequence containers with specifed ordering
* 第68章 Enumeration
    * 68.1 Iteration over an enum
    * 68.2 Scoped enums
    * 68.3 Enum forward declaration in C++11
    * 68.4 Basic Enumeration Declaration
    * 68.5 Enumeration in switch statements
* 第69章 Iteration
    * 69.1 break
    * 69.2 continue
    * 69.3 do
    * 69.4 while
    * 69.5 range-based for loop
    * 69.6 for
* 第70章 Regular expressions
    * 70.1 Basic regex_match and regex_search Examples
    * 70.2 regex_iterator Example
    * 70.3 Anchors
    * 70.4 regex_replace Example
    * 70.5 regex_token_iterator Example
    * 70.6 Quantifiers
    * 70.7 Splitting a string
* 第71章 Implementation-defined behavior
    * 71.1 Size of integral types
    * 71.2 Char might be unsigned or signed
    * 71.3 Ranges of numeric types
    * 71.4 Value representation of floating point types
    * 71.5 Overflow when converting from integer to signed integer
    * 71.6 Underlying type (and hence size) of an enum
    * 71.7 Numeric value of a pointer
    * 71.8 Number of bits in a byte
* 第72章 Exceptions
    * 72.1 Catching exceptions
    * 72.2 Rethrow (propagate) exception
    * 72.3 Best practice: throw by value, catch by const reference
    * 72.4 Custom exception
    * 72.5 std::uncaught_exceptions
    * 72.6 Function Try Block for regular function
    * 72.7 Nested exception
    * 72.8 Function Try Blocks In constructor
    * 72.9 Function Try Blocks In destructor
* 第73章 Lambdas
    * 73.1 What is a lambda expression?
    * 73.2 Specifying the return type
    * 73.3 Capture by value
    * 73.4 Recursive lambdas
    * 73.5 Default capture
    * 73.6 Class lambdas and capture of this
    * 73.7 Capture by reference
    * 73.8 Generic lambdas
    * 73.9 Using lambdas for inline parameter pack unpacking
    * 73.10 Generalized capture
    * 73.11 Conversion to function pointer
    * 73.12 Porting lambda functions to C++03 using functors
* 第74章 Value Categories
    * 74.1 Value Category Meanings
    * 74.2 rvalue
    * 74.3 xvalue
    * 74.4 prvalue
    * 74.5 lvalue
    * 74.6 glvalue
* 第75章 Preprocessor
    * 75.1 Include Guards
    * 75.2 Conditional logic and cross-platform handling
    * 75.3 X-macros
    * 75.4 Macros
    * 75.5 Predefined macros
    * 75.6 Preprocessor Operators
    * 75.7 #pragma once
    * 75.8 Preprocessor error messages
* 第76章 Data Structures in C++
    * 76.1 Linked List implementation in C++
* 第77章 Templates
    * 77.1 Basic Class Template
    * 77.2 Function Templates
    * 77.3 Variadic template data structures
    * 77.4 Argument forwarding
    * 77.5 Partial template specialization
    * 77.6 Template Specialization
    * 77.7 Alias template
    * 77.8 Explicit instantiation
    * 77.9 Non-type template parameter
    * 77.10 Declaring non-type template arguments with auto
    * 77.11 Template template parameters
    * 77.12 Default template parameter value
* 第78章 Expression templates
    * 78.1 A basic example illustrating expression templates
* 第79章 Curiously Recurring Template Pattern (CRTP)
    * 79.1 The Curiously Recurring Template Pattern (CRTP)
    * 79.2 CRTP to avoid code duplication
* 第80章 Threading
    * 80.1 Creating a std::thread
    * 80.2 Passing a reference to a thread
    * 80.3 Using std::async instead of std::thread
    * 80.4 Basic Synchronization
    * 80.5 Create a simple thread pool
    * 80.6 Ensuring a thread is always joined
    * 80.7 Operations on the current thread
    * 80.8 Using Condition Variables
    * 80.9 Thread operations
    * 80.10 Thread-local storage
    * 80.11 Reassigning thread objects
* 第81章 Thread synchronization structures
    * 81.1 std::condition_variable_any, std::cv_status
    * 81.2 std::shared_lock
    * 81.3 std::call_once, std::once_flag
    * 81.4 Object locking for ecient access
* 第82章 The Rule of Three, Five, And Zero
    * 82.1 Rule of Zero
    * 82.2 Rule of Five
    * 82.3 Rule of Three
    * 82.4 Self-assignment Protection
* 第83章 RAII: Resource Acquisition Is Initialization
    * 83.1 Locking
    * 83.2 ScopeSuccess (c++17)
    * 83.3 ScopeFail (c++17)
    * 83.4 Finally/ScopeExit
* 第84章 RTTI: Run-Time Type Information
    * 84.1 dynamic_cast
    * 84.2 The typeid keyword
    * 84.3 Name of a type
    * 84.4 When to use which cast in c++
* 第85章 Mutexes
    * 85.1 Mutex Types
    * 85.2 std::lock
    * 85.3 std::unique_lock, std::shared_lock, std::lock_guard
    * 85.4 Strategies for lock classes: std::try_to_lock, std::adopt_lock, std::defer_lock
    * 85.5 std::mutex
    * 85.6 std::scoped_lock (C++ 17)
* 第86章 Recursive Mutex
    * 86.1 std::recursive_mutex
* 第87章 Semaphore
    * 87.1 Semaphore C++ 11
    * 87.2 Semaphore class in action
* 第88章 Futures and Promises
    * 88.1 Async operation classes
    * 88.2 std::future and std::promise
    * 88.3 Deferred async example
    * 88.4 std::packaged_task and std::future
    * 88.5 std::future_error and std::future_errc
    * 88.6 std::future and std::async
* 第89章 Atomic Types
    * 89.1 Multi-threaded Access
* 第90章 Type Erasure
    * 90.1 A move-only `std::function`
    * 90.2 Erasing down to a Regular type with manual vtable
    * 90.3 Basic mechanism
    * 90.4 Erasing down to a contiguous buer of T
    * 90.5 Type erasing type erasure with std::any
* 第91章 Explicit type conversions
    * 91.1 C-style casting
    * 91.2 Casting away constness
    * 91.3 Base to derived conversion
    * 91.4 Conversion between pointer and integer
    * 91.5 Conversion by explicit constructor or explicit conversion function
    * 91.6 Implicit conversion
    * 91.7 Enum conversions
    * 91.8 Derived to base conversion for pointers to members
    * 91.9 void* to T*
    * 91.10 Type punning conversion
* 第92章 Unnamed types
    * 92.1 Unnamed classes
    * 92.2 As a type alias
    * 92.3 Anonymous members
    * 92.4 Anonymous Union
* 第93章 Type Traits
    * 93.1 Type Properties
    * 93.2 Standard type traits
    * 93.3 Type relations with std::is_same<T, T>
    * 93.4 Fundamental type traits
* 第94章 Return Type Covariance
    * 94.1 Covariant result version of the base example, static type checking
    * 94.2 Covariant smart pointer result (automated cleanup)
* 第95章 Layout of object types
    * 95.1 Class types
    * 95.2 Arithmetic types
    * 95.3 Arrays
* 第96章 Type Inference
    * 96.1 Data Type: Auto
    * 96.2 Lambda auto
    * 96.3 Loops and auto
* 第97章 Typedef and type aliases
    * 97.1 Basic typedef syntax
    * 97.2 More complex uses of typedef
    * 97.3 Declaring multiple types with typedef
    * 97.4 Alias declaration with "using"
* 第98章 type deduction
    * 98.1 Template parameter deduction for constructors
    * 98.2 Auto Type Deduction
    * 98.3 Template Type Deduction
* 第99章 Trailing return type
    * 99.1 Avoid qualifying a nested type name
    * 99.2 Lambda expressions
* 第100章 Alignment
    * 100.1 Controlling alignment
    * 100.2 Querying the alignment of a type
* 第101章 Perfect Forwarding
    * 101.1 Factory functions
* 第102章 decltype
    * 102.1 Basic Example
    * 102.2 Another example
* 第103章 SFINAE (Substitution Failure Is Not An Error)
    * 103.1 What is SFINAE
    * 103.2 void_t
    * 103.3 enable_if
    * 103.4 is_detected
    * 103.5 Overload resolution with a large number of options
    * 103.6 trailing decltype in function templates
    * 103.7 enable_if_all / enable_if_any
* 第104章 Undefined Behavior
    * 104.1 Reading or writing through a null pointer
    * 104.2 Using an uninitialized local variable
    * 104.3 Accessing an out-of-bounds index
    * 104.4 Deleting a derived object via a pointer to a base class that doesn't have a virtual destructor
    * 104.5 Extending the `std` or `posix` Namespace
    * 104.6 Invalid pointer arithmetic
    * 104.7 No return statement for a function with a non-void return type
    * 104.8 Accessing a dangling reference
    * 104.9 Integer division by zero
    * 104.10 Shifting by an invalid number of positions
    * 104.11 Incorrect pairing of memory allocation and deallocation
    * 104.12 Signed Integer Overflow
    * 104.13 Multiple non-identical definitions (the One Definition Rule)
    * 104.14 Modifying a const object
    * 104.15 Returning from a [[noreturn]] function
    * 104.16 Infinite template recursion
    * 104.17 Overflow during conversion to or from floating point type
    * 104.18 Modifying a string literal
    * 104.19 Accessing an object as the wrong type
    * 104.20 Invalid derived-to-base conversion for pointers to members
    * 104.21 Destroying an object that has already been destroyed
    * 104.22 Access to nonexistent member through pointer to member
    * 104.23 Invalid base-to-derived static cast
    * 104.24 Floating point overflow
    * 104.25 Calling (Pure) Virtual Members From Constructor Or Destructor
    * 104.26 Function call through mismatched function pointer type
* 第105章 Overload resolution
    * 105.1 Categorization of argument to parameter cost
    * 105.2 Arithmetic promotions and conversions
    * 105.3 Overloading on Forwarding Reference
    * 105.4 Exact match
    * 105.5 Overloading on constness and volatility
    * 105.6 Name lookup and access checking
    * 105.7 Overloading within a class hierarchy
    * 105.8 Steps of Overload Resolution
* 第106章 Move Semantics
    * 106.1 Move semantics
    * 106.2 Using std::move to reduce complexity from O(n²) to O(n)
    * 106.3 Move constructor
    * 106.4 Re-use a moved object
    * 106.5 Move assignment
    * 106.6 Using move semantics on containers
* 第107章 Pimpl Idiom
    * 107.1 Basic Pimpl idiom
* 第108章 auto
    * 108.1 Basic auto sample
    * 108.2 Generic lambda (C++14)
    * 108.3 auto and proxy objects
    * 108.4 auto and Expression Templates
    * 108.5 auto, const, and references
    * 108.6 Trailing return type
* 第109章 Copy Elision
    * 109.1 Purpose of copy elision
    * 109.2 Guaranteed copy elision
    * 109.3 Parameter elision
    * 109.4 Return value elision
    * 109.5 Named return value elision
    * 109.6 Copy initialization elision
* 第110章 Fold Expressions
    * 110.1 Unary Folds
    * 110.2 Binary Folds
    * 110.3 Folding over a comma
* 第111章 Unions
    * 111.1 Undefined Behavior
    * 111.2 Basic Union Features
    * 111.3 Typical Use
* 第112章 Design pattern implementation in C++
    * 112.1 Adapter Pattern
    * 112.2 Observer pattern
    * 112.3 Factory Pattern
    * 112.4 Builder Pattern with Fluent API
* 第113章 Singleton Design Pattern
    * 113.1 Lazy Initialization
    * 113.2 Static deinitialization-safe singleton
    * 113.3 Thread-safe Singeton
    * 113.4 Subclasses
* 第114章 User-Defined Literals
    * 114.1 Self-made user-defined literal for binary
    * 114.2 Standard user-defined literals for duration
    * 114.3 User-defined literals with long double values
    * 114.4 Standard user-defined literals for strings
    * 114.5 Standard user-defined literals for complex
* 第115章 Memory management
    * 115.1 Free Storage (Heap, Dynamic Allocation)
    * 115.2 Placement new
    * 115.3 Stack
* 第116章 C++11 Memory Model
    * 116.1 Need for Memory Model
    * 116.2 Fence example
* 第117章 Scopes
    * 117.1 Global variables
    * 117.2 Simple block scope
* 第118章 static_assert
    * 118.1 static_assert
* 第119章 constexpr
    * 119.1 constexpr variables
    * 119.2 Static if statement
    * 119.3 constexpr functions
* 第120章 One Definition Rule (ODR)
    * 120.1 ODR violation via overload resolution
    * 120.2 Multiply defined function
    * 120.3 Inline functions
* 第121章 Unspecified behavior
    * 121.1 Value of an out-of-range enum
    * 121.2 Evaluation order of function arguments
    * 121.3 Result of some reinterpret_cast conversions
    * 121.4 Space occupied by a reference
    * 121.5 Moved-from state of most standard library classes
    * 121.6 Result of some pointer comparisons
    * 121.7 Static cast from bogus void* value
    * 121.8 Order of initialization of globals across TU
* 第122章 Argument Dependent Name Lookup
    * 122.1 What functions are found
* 第123章 Attributes
    * 123.1 [[fallthrough]]
    * 123.2 [[nodiscard]]
    * 123.3 [[deprecated]] and [[deprecated("reason")]]
    * 123.4 [[maybe_unused]]
    * 123.5 [[noreturn]]
* 第124章 Recursion in C++
    * 124.1 Using tail recursion and Fibonnaci-style recursion to solve the Fibonnaci sequence
    * 124.2 Recursion with memoization
* 第125章 Arithmitic Metaprogramming
    * 125.1 Calculating power in O(log n)
* 第126章 Callable Objects
    * 126.1 Function Pointers
    * 126.2 Classes with operator() (Functors)
* 第127章 Client server examples
    * 127.1 Hello TCP Client
    * 127.2 Hello TCP Server
* 第128章 Const Correctness
    * 128.1 The Basics
    * 128.2 Const Correct Class Design
    * 128.3 Const Correct Function Parameters
    * 128.4 Const Correctness as Documentation
* 第129章 Parameter packs
    * 129.1 A template with a parameter pack
    * 129.2 Expansion of a parameter pack
* 第130章 Build Systems
    * 130.1 Generating Build Environment with CMake
    * 130.2 Compiling with GNU make
    * 130.3 Building with SCons
    * 130.4 Autotools (GNU)
    * 130.5 Ninja
    * 130.6 NMAKE (Microsoft Program Maintenance Utility)
* 第131章 Concurrency With OpenMP
    * 131.1 OpenMP: Parall  *s
    * 131.2 OpenMP: Parall  *s
    * 131.3 OpenMP: Parallel For Loop
    * 131.4 OpenMP: Parallel Gathering / Reduction
* 第132章 Resource Management
    * 132.1 Resource Acquisition Is Initialization
    * 132.2 Mutexes & Thread Safety
* 第133章 Storage class specifiers
    * 133.1 extern
    * 133.2 register
    * 133.3 static
    * 133.4 auto
    * 133.5 mutable
* 第134章 Linkage specifications
    * 134.1 Signal handler for Unix-like operating system
    * 134.2 Making a C library header compatible with C++
* 第135章 Digit separators
    * 135.1 Digit Separator
* 第136章 C incompatibilities
    * 136.1 Reserved Keywords
    * 136.2 Weakly typed pointers
    * 136.3 goto or switch
* 第137章 Side by Side Comparisons of classic C++ examples solved via C++ vs C++11vs C++14 vs C++17
    * 137.1 Looping through a container
* 第138章 Compiling and Building
    * 138.1 Compiling with GCC
    * 138.2 Compiling with Visual Studio (Graphical Interface) - Hello World
    * 138.3 Online Compilers
    * 138.4 Compiling with Visual C++ (Command Line)
    * 138.5 Compiling with Clang
    * 138.6 The C++ compilation process
    * 138.7 Compiling with Code::Blocks (Graphical interface)
* 第139章 Common compile/linker errors (GCC)
    * 139.1 undefined reference to `***'
    * 139.2 error: '***' was not declared in this scope
    * 139.3 fatal error: ***: No such file or directory
* 第140章 More undefined behaviors in C++
    * 140.1 Referring to non-static members in initializer lists
* 第141章 Unit Testing in C++
    * 141.1 Google Test
    * 141.2 Catch
* 第142章 C++ Debugging and Debug-prevention Tools & Techniques
    * 142.1 Static analysis
    * 142.2 Segfault analysis with GDB
    * 142.3 Clean code
* 第143章 Optimization in C++
    * 143.1 Introduction to performance
    * 143.2 Empty Base Class Optimization
    * 143.3 Optimizing by executing less code
    * 143.4 Using ecient containers
    * 143.5 Small Object Optimization
* 第144章 Optimization
    * 144.1 Inline Expansion/Inlining
    * 144.2 Empty base optimization
* 第145章 Profiling
    * 145.1 Profiling with gcc and gprof
    * 145.2 Generating callgraph diagrams with gperf2dot
    * 145.3 Profiling CPU Usage with gcc and Google Perf Tools
* 第146章 Refactoring Techniques
    * 146.1 Goto Cleanup