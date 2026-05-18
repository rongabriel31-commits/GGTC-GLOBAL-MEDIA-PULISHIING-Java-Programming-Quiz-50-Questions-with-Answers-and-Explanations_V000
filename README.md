# GGTC-GLOBAL-MEDIA-PULISHIING-Java-Programming-Quiz-50-Questions-with-Answers-and-Explanations_V000
A part of the Better Reading Series Education program GGTC 


1. What is Java?

Answer: Java is a high-level, object-oriented programming language designed to be platform-independent.

Explanation: Java code is compiled into bytecode, which runs on the Java Virtual Machine (JVM). This is why Java follows the idea of “write once, run anywhere.”

⸻

2. What is the JVM?

Answer: JVM stands for Java Virtual Machine.

Explanation: The JVM executes Java bytecode and allows Java programs to run on different operating systems without modification.

⸻

3. What is the difference between JDK, JRE, and JVM?

Answer:

* JDK: Java Development Kit
* JRE: Java Runtime Environment
* JVM: Java Virtual Machine

Explanation: The JDK includes tools for developing Java programs, the JRE provides libraries and runtime support, and the JVM actually runs the bytecode.

⸻

4. What is bytecode?

Answer: Bytecode is the intermediate code generated when a Java program is compiled.

Explanation: The Java compiler converts source code into .class files containing bytecode, which the JVM interprets or compiles further.

⸻

5. What is the main method in Java?

Answer:

public static void main(String[] args)

Explanation: This is the entry point of a Java application. The JVM starts program execution from this method.

⸻

6. What does public mean in Java?

Answer: public is an access modifier that makes a class, method, or variable accessible from anywhere.

Explanation: If a method is public, it can be called from other classes.

⸻

7. What does static mean in Java?

Answer: static means the member belongs to the class rather than to an instance of the class.

Explanation: A static method can be called without creating an object.

⸻

8. What does void mean in Java?

Answer: void means the method does not return any value.

Explanation: Methods with void perform actions but do not send back a result.

⸻

9. What is an object in Java?

Answer: An object is an instance of a class.

Explanation: A class is a blueprint, and an object is the actual thing created from that blueprint.

⸻

10. What is a class in Java?

Answer: A class is a template for creating objects.

Explanation: It defines fields and methods that its objects will have.

⸻

11. What is encapsulation?

Answer: Encapsulation is wrapping data and methods into a single unit and controlling access to them.

Explanation: This is usually done using private variables and public getter/setter methods.

⸻

12. What is inheritance?

Answer: Inheritance allows one class to acquire the properties and behaviors of another class.

Explanation: It promotes code reuse. A subclass extends a superclass.

⸻

13. What is polymorphism?

Answer: Polymorphism allows one interface or method name to be used for different underlying forms.

Explanation: In Java, this commonly appears through method overriding and method overloading.

⸻

14. What is abstraction?

Answer: Abstraction means hiding implementation details and showing only essential features.

Explanation: Abstract classes and interfaces are used to achieve abstraction in Java.

⸻

15. What is a constructor?

Answer: A constructor is a special method used to initialize objects.

Explanation: It has the same name as the class and no return type.

⸻

16. Can a constructor be inherited?

Answer: No, constructors are not inherited.

Explanation: A subclass may call a superclass constructor using super(), but it does not inherit it.

⸻

17. What is method overloading?

Answer: Method overloading means defining multiple methods with the same name but different parameter lists.

Explanation: It allows similar operations with different inputs.

⸻

18. What is method overriding?

Answer: Method overriding occurs when a subclass provides its own version of a method already defined in its superclass.

Explanation: This supports runtime polymorphism.

⸻

19. What is the difference between overloading and overriding?

Answer:

* Overloading: same method name, different parameters, same class or inheritance chain
* Overriding: same method signature, subclass replaces superclass method

Explanation: Overloading is resolved at compile time. Overriding is resolved at runtime.

⸻

20. What is the this keyword?

Answer: this refers to the current object.

Explanation: It is used to distinguish instance variables from parameters and to call another constructor in the same class.

⸻

21. What is the super keyword?

Answer: super refers to the immediate parent class object.

Explanation: It is used to call superclass methods and constructors.

⸻

22. What is an interface?

Answer: An interface is a contract that classes can implement.

Explanation: It defines methods a class must provide, supporting abstraction and multiple inheritance of type.

⸻

23. Can Java support multiple inheritance?

Answer: Java does not support multiple inheritance of classes, but it supports multiple inheritance through interfaces.

Explanation: A class can implement multiple interfaces.

⸻

24. What is an abstract class?

Answer: An abstract class is a class that cannot be instantiated and may contain abstract methods.

Explanation: It is used when a base class should provide common behavior but not be created directly.

⸻

25. What is the difference between an abstract class and an interface?

Answer:

* Abstract class can have instance variables, constructors, and concrete methods
* Interface mainly defines behavior contracts

Explanation: Interfaces are better for capability definitions; abstract classes are useful for shared base functionality.

⸻

26. What are primitive data types in Java?

Answer: byte, short, int, long, float, double, char, boolean

Explanation: These are the basic built-in types that store simple values.

⸻

27. What is the default value of an int instance variable?

Answer: 0

Explanation: Instance variables receive default values if not explicitly initialized. Local variables do not.

⸻

28. What is the difference between == and .equals()?

Answer:

* == compares references for objects
* .equals() compares content, if overridden properly

Explanation: For strings and custom objects, .equals() is usually used for logical comparison.

⸻

29. Why are strings immutable in Java?

Answer: Strings cannot be changed after creation.

Explanation: Immutability improves security, thread safety, and efficiency through string pooling.

⸻

30. What is the difference between String, StringBuilder, and StringBuffer?

Answer:

* String: immutable
* StringBuilder: mutable, not synchronized
* StringBuffer: mutable, synchronized

Explanation: StringBuilder is usually preferred when building strings in a single-threaded context.

⸻

31. What is an array in Java?

Answer: An array is a fixed-size collection of elements of the same type.

Explanation: Arrays store multiple values under one variable name and use indexes starting at 0.

⸻

32. What happens if you access an invalid array index?

Answer: Java throws an ArrayIndexOutOfBoundsException.

Explanation: This happens when the index is less than 0 or greater than or equal to the array length.

⸻

33. What is a package in Java?

Answer: A package is a namespace used to organize classes and interfaces.

Explanation: Packages help avoid naming conflicts and improve project structure.

⸻

34. What is exception handling?

Answer: Exception handling is the process of managing runtime errors so the program can continue or fail gracefully.

Explanation: Java uses try, catch, finally, throw, and throws.

⸻

35. What is the difference between checked and unchecked exceptions?

Answer:

* Checked exceptions must be handled or declared
* Unchecked exceptions do not have to be handled explicitly

Explanation: Checked exceptions are verified at compile time. Unchecked exceptions are subclasses of RuntimeException.

⸻

36. What is the purpose of the finally block?

Answer: The finally block executes whether or not an exception occurs.

Explanation: It is commonly used for cleanup, such as closing files or database connections.

⸻

37. What is a NullPointerException?

Answer: It occurs when you try to use an object reference that is null.

Explanation: For example, calling a method on a null object causes this exception.

⸻

38. What is the difference between throw and throws?

Answer:

* throw is used to actually throw an exception
* throws declares that a method may throw exceptions

Explanation: throw appears inside method bodies; throws appears in method signatures.

⸻

39. What is the Java Collection Framework?

Answer: It is a set of classes and interfaces for storing and manipulating groups of objects.

Explanation: It includes interfaces like List, Set, Map, and classes like ArrayList, HashSet, and HashMap.

⸻

40. What is the difference between ArrayList and LinkedList?

Answer:

* ArrayList uses a dynamic array
* LinkedList uses linked nodes

Explanation: ArrayList is faster for random access; LinkedList can be better for frequent insertions and deletions in the middle.

⸻

41. What is the difference between List and Set?

Answer:

* List allows duplicates and preserves order
* Set does not allow duplicates

Explanation: Use List when order matters and duplicates are allowed; use Set when uniqueness matters.

⸻

42. What is a Map in Java?

Answer: A Map stores key-value pairs.

Explanation: Keys must be unique. Common implementations include HashMap, TreeMap, and LinkedHashMap.

⸻

43. What is the difference between HashMap and TreeMap?

Answer:

* HashMap stores data in no guaranteed order
* TreeMap stores keys in sorted order

Explanation: TreeMap is slower than HashMap in many cases because it maintains sorting.

⸻

44. What is autoboxing in Java?

Answer: Autoboxing is the automatic conversion of a primitive type into its corresponding wrapper class.

Explanation: For example, int becomes Integer.

⸻

45. What is unboxing in Java?

Answer: Unboxing is the automatic conversion of a wrapper object into its primitive type.

Explanation: For example, Integer becomes int.

⸻

46. What is multithreading?

Answer: Multithreading is the ability to run multiple threads concurrently.

Explanation: It allows programs to perform several tasks at the same time.

⸻

47. How do you create a thread in Java?

Answer: By extending Thread or implementing Runnable.

Explanation: Implementing Runnable is generally preferred because it separates the task from the thread object.

⸻

48. What is synchronization in Java?

Answer: Synchronization controls access to shared resources by multiple threads.

Explanation: It prevents data inconsistency caused by concurrent execution.

⸻

49. What is the difference between compile-time and runtime errors?

Answer:

* Compile-time errors are found by the compiler before execution
* Runtime errors occur while the program is running

Explanation: Syntax mistakes are compile-time errors; exceptions are usually runtime errors.

⸻

50. What is garbage collection in Java?

Answer: Garbage collection is Java’s automatic memory management process.

Explanation: The JVM removes objects that are no longer referenced, helping prevent memory leaks from manual memory handling.

⸻

Bonus Mini-Practice Format

Here are 5 quick recall prompts from the quiz:

1. What keyword refers to the current object?
    Answer: this
2. Which collection does not allow duplicates?
    Answer: Set
3. What is the entry point of a Java program?
    Answer: main method
4. Which class is mutable: String or StringBuilder?
    Answer: StringBuilder
5. What exception occurs when using a null reference?
    Answer: NullPointerException

If you want this turned into a multiple-choice quiz, PDF study sheet, or DOCX handout, say which format.


===============#######==================

Java Programming Quiz — 100 Questions, Answers, and Explanations

Below is a more complete, library-ready version. It is organized for reuse in study materials, worksheets, or quiz banks.

⸻

1. What is Java?

Answer: Java is a high-level, object-oriented programming language.

Explanation: It was designed to be readable, portable, and secure. Java applications are commonly used for web, desktop, mobile, and enterprise systems.

⸻

2. What does “platform-independent” mean in Java?

Answer: It means Java code can run on different operating systems without being rewritten.

Explanation: Java source code is compiled into bytecode, which is executed by the Java Virtual Machine (JVM) on any supported platform.

⸻

3. What is the JVM?

Answer: JVM stands for Java Virtual Machine.

Explanation: The JVM runs Java bytecode. It acts as the environment that allows Java programs to execute on many different systems.

⸻

4. What is the JDK?

Answer: JDK stands for Java Development Kit.

Explanation: The JDK includes the compiler, tools, and libraries needed to write and build Java programs.

⸻

5. What is the JRE?

Answer: JRE stands for Java Runtime Environment.

Explanation: The JRE includes the JVM and supporting libraries needed to run Java programs, but not the development tools.

⸻

6. What is bytecode?

Answer: Bytecode is the intermediate code produced by the Java compiler.

Explanation: The compiler converts .java files into .class files containing bytecode, which the JVM can run.

⸻

7. What is the main purpose of the main method?

Answer: It is the entry point of a Java application.

Explanation: When a standalone Java program starts, the JVM looks for the main method first.

⸻

8. What is the correct signature of the Java main method?

Answer: public static void main(String[] args)

Explanation: This exact form allows the JVM to start the application properly.

⸻

9. What does public mean in Java?

Answer: public means the member is accessible from any other class.

Explanation: Access modifiers control visibility. public is the most open level.

⸻

10. What does private mean in Java?

Answer: private means the member is accessible only within its own class.

Explanation: It is commonly used to protect data and support encapsulation.

⸻

11. What does static mean in Java?

Answer: static means the member belongs to the class rather than to an object instance.

Explanation: A static field or method can be accessed without creating an object.

⸻

12. What does void mean in a method declaration?

Answer: void means the method does not return a value.

Explanation: The method may perform work, but it does not send a result back to the caller.

⸻

13. What is a class in Java?

Answer: A class is a blueprint for creating objects.

Explanation: It defines the data and behavior that objects of that type will have.

⸻

14. What is an object in Java?

Answer: An object is an instance of a class.

Explanation: If a class is a blueprint, an object is the actual item created from it.

⸻

15. What is a method?

Answer: A method is a block of code that performs a task.

Explanation: Methods define behavior for objects or classes and help organize program logic.

⸻

16. What is a variable?

Answer: A variable is a named storage location for data.

Explanation: Variables allow programs to hold values such as numbers, text, or object references.

⸻

17. What is a primitive data type?

Answer: A primitive data type is a basic built-in type that stores a simple value.

Explanation: Java has eight primitive types, including int, double, and boolean.

⸻

18. Name the eight primitive data types in Java.

Answer: byte, short, int, long, float, double, char, boolean

Explanation: These types are built into the language and are not objects.

⸻

19. What is the difference between int and double?

Answer: int stores whole numbers, while double stores decimal numbers.

Explanation: Use int for values like 5, and double for values like 5.75.

⸻

20. What does boolean store?

Answer: It stores true or false.

Explanation: Booleans are used in conditions, comparisons, and logical operations.

⸻

21. What does char store?

Answer: It stores a single character.

Explanation: For example, 'A', 'b', and '7' are character values.

⸻

22. What is a String in Java?

Answer: A String is an object used to store text.

Explanation: Unlike char, which stores one character, String stores sequences of characters.

⸻

23. Are Strings primitive types in Java?

Answer: No, Strings are objects.

Explanation: String is a class in Java, not one of the eight primitive types.

⸻

24. What does it mean that Strings are immutable?

Answer: It means a String cannot be changed after it is created.

Explanation: Any apparent change creates a new String object instead of modifying the old one.

⸻

25. What is a constructor?

Answer: A constructor is a special method used to initialize objects.

Explanation: It has the same name as the class and runs when an object is created.

⸻

26. Can a constructor have a return type?

Answer: No, constructors do not have a return type.

Explanation: If a method has a return type, it is not a constructor.

⸻

27. What is the default constructor?

Answer: It is a constructor with no parameters.

Explanation: Java provides one automatically only if no constructor is written in the class.

⸻

28. What is method overloading?

Answer: Method overloading means having multiple methods with the same name but different parameter lists.

Explanation: This allows similar actions to be performed with different kinds or numbers of inputs.

⸻

29. What is method overriding?

Answer: Method overriding happens when a subclass provides its own version of a superclass method.

Explanation: The overriding method must have the same name and parameter list.

⸻

30. What is the difference between overloading and overriding?

Answer: Overloading uses different parameter lists; overriding replaces inherited behavior in a subclass.

Explanation: Overloading is resolved at compile time, while overriding is resolved at runtime.

⸻

31. What is inheritance?

Answer: Inheritance allows one class to acquire properties and behaviors from another class.

Explanation: This supports code reuse and creates parent-child relationships between classes.

⸻

32. What keyword is used for inheritance in Java?

Answer: extends

Explanation: A subclass extends a superclass to inherit its accessible members.

⸻

33. What is polymorphism?

Answer: Polymorphism allows the same method name or reference type to behave differently depending on the object involved.

Explanation: It is one of the core principles of object-oriented programming.

⸻

34. What is encapsulation?

Answer: Encapsulation is bundling data and methods together while controlling access to the data.

Explanation: It is often implemented with private fields and public getter/setter methods.

⸻

35. What is abstraction?

Answer: Abstraction means hiding unnecessary implementation details and showing only essential features.

Explanation: It helps simplify complex systems.

⸻

36. What is an abstract class?

Answer: An abstract class is a class that cannot be instantiated directly.

Explanation: It may contain abstract methods as well as regular methods.

⸻

37. What is an abstract method?

Answer: An abstract method is a method declared without a body.

Explanation: Subclasses must provide its implementation unless they are also abstract.

⸻

38. What is an interface?

Answer: An interface is a contract that defines methods a class must implement.

Explanation: It supports abstraction and allows Java to achieve multiple inheritance of type.

⸻

39. Can a class implement more than one interface?

Answer: Yes.

Explanation: Java does not allow multiple inheritance of classes, but it does allow multiple interfaces.

⸻

40. What is the difference between an interface and an abstract class?

Answer: An abstract class can have state and implemented methods; an interface primarily defines behavior contracts.

Explanation: Use an abstract class for shared base functionality and an interface for common capability definitions.

⸻

41. What keyword refers to the current object?

Answer: this

Explanation: It is used to refer to the current instance and resolve naming conflicts.

⸻

42. What keyword refers to the parent class?

Answer: super

Explanation: It is used to access superclass constructors, methods, and fields.

⸻

43. What is an array?

Answer: An array is a fixed-size structure that stores multiple values of the same type.

Explanation: Each value is stored at an index beginning at 0.

⸻

44. How do array indexes work in Java?

Answer: Array indexes start at 0.

Explanation: The first element is at index 0, the second at 1, and so on.

⸻

45. What happens if you access an invalid array index?

Answer: Java throws an ArrayIndexOutOfBoundsException.

Explanation: This error occurs when the index is less than 0 or greater than the last valid index.

⸻

46. What is the length property of an array used for?

Answer: It tells you how many elements are in the array.

Explanation: array.length is commonly used in loops to avoid going out of bounds.

⸻

47. What is a package in Java?

Answer: A package is a way to organize related classes and interfaces.

Explanation: Packages help keep projects structured and prevent name conflicts.

⸻

48. What keyword is used to bring another class or package member into a file?

Answer: import

Explanation: Import statements make it easier to use classes from other packages.

⸻

49. What is a loop?

Answer: A loop is a control structure that repeats code.

Explanation: Java provides several loop types for repeated execution.

⸻

50. Name three types of loops in Java.

Answer: for, while, and do-while

Explanation: Each loop type is useful in different situations depending on how the repetition should work.

⸻

51. What is the difference between while and do-while?

Answer: while checks the condition before running; do-while checks it after running once.

Explanation: A do-while loop always runs at least one time.

⸻

52. What is an if statement?

Answer: An if statement executes code only when a condition is true.

Explanation: It is used for decision-making in programs.

⸻

53. What is an else statement?

Answer: else provides an alternative block of code when the if condition is false.

Explanation: It works with if to handle different outcomes.

⸻

54. What is an else if statement?

Answer: else if allows checking multiple conditions in sequence.

Explanation: It is useful when there are several possible cases.

⸻

55. What is a switch statement?

Answer: A switch statement selects one block of code from many possible options.

Explanation: It is often cleaner than many else if statements when comparing one variable against several values.

⸻

56. What does break do in Java?

Answer: break immediately stops a loop or exits a switch.

Explanation: It is used to end execution early when needed.

⸻

57. What does continue do in Java?

Answer: continue skips the rest of the current loop iteration and moves to the next one.

Explanation: It is useful when certain cases should be ignored without ending the loop.

⸻

58. What is a return statement?

Answer: A return statement sends a value back from a method or ends the method.

Explanation: In non-void methods, it must return a value of the correct type.

⸻

59. What is the difference between local variables and instance variables?

Answer: Local variables are declared inside methods; instance variables are declared in a class but outside methods.

Explanation: Instance variables belong to objects, while local variables exist only during method execution.

⸻

60. Are local variables automatically initialized in Java?

Answer: No.

Explanation: Local variables must be assigned a value before they are used.

⸻

61. What is the default value of an int instance variable?

Answer: 0

Explanation: Instance variables get default values if not explicitly initialized.

⸻

62. What is the default value of a boolean instance variable?

Answer: false

Explanation: Like other instance variables, booleans receive a default value automatically.

⸻

63. What is the default value of an object reference instance variable?

Answer: null

Explanation: null means the reference does not currently point to any object.

⸻

64. What is null in Java?

Answer: null is a special value meaning “no object reference.”

Explanation: Trying to use a null reference like a real object causes an error.

⸻

65. What is a NullPointerException?

Answer: It is an exception thrown when code tries to use an object reference that is null.

Explanation: For example, calling a method on a null reference will cause this error.

⸻

66. What is exception handling?

Answer: Exception handling is the process of managing errors that occur during program execution.

Explanation: It prevents the program from crashing unexpectedly and allows controlled responses to errors.

⸻

67. What keywords are commonly used in exception handling?

Answer: try, catch, finally, throw, and throws

Explanation: These keywords define how exceptions are detected, handled, or passed upward.

⸻

68. What does a try block do?

Answer: A try block contains code that may throw an exception.

Explanation: It is followed by one or more catch blocks and sometimes a finally block.

⸻

69. What does a catch block do?

Answer: A catch block handles an exception thrown in the try block.

Explanation: It allows the program to respond to a specific type of error.

⸻

70. What does a finally block do?

Answer: A finally block executes whether or not an exception occurs.

Explanation: It is often used for cleanup tasks like closing files or connections.

⸻

71. What is the difference between throw and throws?

Answer: throw is used to actually throw an exception; throws declares that a method may throw exceptions.

Explanation: One is used inside a method body, and the other in the method signature.

⸻

72. What is a checked exception?

Answer: A checked exception must be handled or declared.

Explanation: The compiler enforces this rule to make error handling explicit.

⸻

73. What is an unchecked exception?

Answer: An unchecked exception is an exception that does not have to be declared or caught.

Explanation: These are usually subclasses of RuntimeException.

⸻

74. What is the difference between == and .equals()?

Answer: == compares references for objects, while .equals() compares content when properly overridden.

Explanation: With objects like Strings, .equals() is usually the correct choice for logical comparison.

⸻

75. What is autoboxing?

Answer: Autoboxing is automatic conversion of a primitive into its wrapper object.

Explanation: For example, Java can convert int to Integer automatically.

⸻

76. What is unboxing?

Answer: Unboxing is automatic conversion of a wrapper object into its primitive value.

Explanation: For example, Java can convert Integer to int automatically.

⸻

77. What is a wrapper class?

Answer: A wrapper class is an object form of a primitive type.

Explanation: Examples include Integer, Double, Character, and Boolean.

⸻

78. What is the Java Collection Framework?

Answer: It is a set of classes and interfaces for storing and managing groups of objects.

Explanation: It provides ready-made data structures like lists, sets, and maps.

⸻

79. What is a List in Java?

Answer: A List is a collection that maintains insertion order and allows duplicates.

Explanation: Examples include ArrayList and LinkedList.

⸻

80. What is a Set in Java?

Answer: A Set is a collection that does not allow duplicate elements.

Explanation: It is useful when uniqueness matters more than order.

⸻

81. What is a Map in Java?

Answer: A Map stores data as key-value pairs.

Explanation: Each key must be unique, and each key maps to a value.

⸻

82. What is an ArrayList?

Answer: ArrayList is a resizable array implementation of the List interface.

Explanation: It is commonly used because it is easy to work with and provides fast indexed access.

⸻

83. What is a LinkedList?

Answer: LinkedList is a list implementation based on linked nodes.

Explanation: It can be useful for insertions and deletions, especially in the middle of the list.

⸻

84. What is a HashSet?

Answer: HashSet is a set implementation that stores unique elements with no guaranteed order.

Explanation: It is commonly used when fast lookup and uniqueness are needed.

⸻

85. What is a HashMap?

Answer: HashMap is a map implementation that stores key-value pairs with no guaranteed ordering.

Explanation: It is widely used because of its efficient lookup performance.

⸻

86. What is the difference between ArrayList and LinkedList?

Answer: ArrayList is usually better for fast random access, while LinkedList can be better for frequent insertions and deletions.

Explanation: Their internal structures are different, so performance depends on use case.

⸻

87. What is the difference between List and Set?

Answer: A List allows duplicates and preserves order; a Set does not allow duplicates.

Explanation: Choose based on whether repeated values and ordering matter.

⸻

88. What is the difference between HashMap and TreeMap?

Answer: HashMap does not keep keys sorted, while TreeMap stores keys in sorted order.

Explanation: TreeMap is useful when ordered keys are required.

⸻

89. What is a for-each loop?

Answer: A for-each loop is a simplified loop used to iterate through arrays or collections.

Explanation: It is easier to read when you do not need the index.

⸻

90. What is recursion?

Answer: Recursion is when a method calls itself.

Explanation: Recursive solutions can be elegant, but they must have a stopping condition to avoid infinite calls.

⸻

91. What is the purpose of comments in Java?

Answer: Comments are notes in the code meant for human readers.

Explanation: They improve readability and documentation and are ignored by the compiler.

⸻

92. What are the three main types of comments in Java?

Answer: Single-line comments, multi-line comments, and documentation comments.

Explanation: These are written using //, /* */, and /** */.

⸻

93. What is garbage collection in Java?

Answer: Garbage collection is Java’s automatic process for freeing memory used by unreachable objects.

Explanation: It helps manage memory without manual deallocation.

⸻

94. What is memory leak risk in Java if garbage collection exists?

Answer: Memory problems can still happen if references to unused objects are kept unnecessarily.

Explanation: Garbage collection only removes objects that are no longer reachable.

⸻

95. What is multithreading?

Answer: Multithreading is running multiple threads within a program at the same time.

Explanation: It helps programs perform multiple tasks concurrently.

⸻

96. What is a thread?

Answer: A thread is a single path of execution within a program.

Explanation: A program can have multiple threads working at once.

⸻

97. How can you create a thread in Java?

Answer: By extending Thread or implementing Runnable.

Explanation: Implementing Runnable is generally preferred because it separates task logic from thread control.

⸻

98. What is synchronization in Java?

Answer: Synchronization controls access to shared data when multiple threads use it.

Explanation: It helps prevent inconsistent results caused by race conditions.

⸻

99. What is the difference between compile-time errors and runtime errors?

Answer: Compile-time errors are found before execution; runtime errors happen while the program is running.

Explanation: Syntax mistakes are compile-time errors, while exceptions often occur at runtime.

⸻

100. Why is Java considered object-oriented?

Answer: Because it organizes programs around classes and objects and supports encapsulation, inheritance, polymorphism, and abstraction.

Explanation: These features make Java a strong example of object-oriented design.

⸻

Quick Answer Key Snapshot

Core Terms

* Java: high-level, object-oriented language
* JVM: runs bytecode
* JDK: development tools
* JRE: runtime environment
* Bytecode: compiled intermediate form

OOP Concepts

* Encapsulation: protect and organize data
* Inheritance: one class extends another
* Polymorphism: one interface, many forms
* Abstraction: hide unnecessary detail

Common Error Concepts

* NullPointerException: using a null reference
* ArrayIndexOutOfBoundsException: invalid array index
* Checked exception: must be handled/declared
* Unchecked exception: not required to be handled

Collections

* List: ordered, allows duplicates
* Set: no duplicates
* Map: key-value pairs
* ArrayList: resizable array
* HashMap: key-value storage, no guaranteed order

⸻

Optional Classroom Use Format

Suggested scoring model

* 1 point per correct answer
* 100 points total
* Add 1 bonus point per correct explanation expansion if used as a written assessment

Suggested difficulty bands

* Questions 1–30: beginner
* Questions 31–70: lower-intermediate
* Questions 71–100: intermediate

⸻

Short Sample Multiple-Choice Conversion

1. What does JVM stand for?

A. Java Variable Method
B. Java Virtual Machine
C. Joint Virtual Module
D. Java Verified Memory

Answer: B
Explanation: JVM means Java Virtual Machine, the environment that runs Java bytecode.

2. Which collection does not allow duplicate elements?

A. List
B. ArrayList
C. Set
D. Map

Answer: C
Explanation: A Set is designed to store unique elements only.

3. What keyword refers to the current object?

A. super
B. this
C. self
D. current

Answer: B
Explanation: this refers to the current instance of the class.

⸻

If you want, I can turn this next into a clean exam-bank format, a numbered worksheet with no divider lines, or a DOCX/PDF library handout layout.
