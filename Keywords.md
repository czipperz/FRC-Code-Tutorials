#Keywords

Java is an object oriented language and uses different keywords so that it will never be confused, and the programmer knows *exactly* what they are getting. Most classes are a blueprint to creating objects. In robotics programming we will use the WPILIBJ software so that we don't have to deal with the drivers, and just with the original code. Heres a little list of keywords.

* Visibility - `public`, `private`, `protected`
* Mutability - `static` - allows a class to declare methods or variables that are to be shared and don't need an instance to be used, and or `final` - declares a variable as *immutable*, or non-changeable.
* Inheritance
* - `abstract` - used to describe classes as not being able to create objects, but still being able to define methods' bodies.
* - `final` - removes the option for a class to be extended. A class **cannot** be both be both `abstract` and `final`.
* Primitives - `int`, `double`, `boolean`, `byte`, `long`, `char`, `float`, `short`
* Variables - any Primitive or a class name.
* Methods - the return type of a method can be `void` or a Variable type. Methods can use a Visibility keyword as the first word in their declaration or none for the default.
* Types of files - `class` - can be final or abstract, `interface`, `enum` - a list of values.
* Testing
* - `if` statements are used to test boolean conditions and then execute a block of code. Use `else` after an if statement to show a block of code to execute if the if statement is not fulfilled.
* - `switch` performs an `==` if statement on a list of `case`s.
* Blocks are started with `{` and end with `}`
* Looping - `for`, `do` executes a piece of code which must end with a `while` statement that shows whether to do it again, `while`. These allow you to repetitively execute a block of code over a list or amount of time.
* - Use `break` to exit the current loop.
* Exceptions - these aren't used in robotics programming so I'll just briefly cover them now.
* - `throw` will exit the current method abruptly and force the method that called it to try to handle it.
* - `throws` declares that the method has the possibility to throw an exception. You only need to declare these for non *runtime* exceptions.
* - `try` will try to execute the next block of code. at the end of the block, you need to put a catch block. They are required for normal exceptions, but are *not* requiried for runtime exceptions.
* - - `catch` ends a try block and will describe what will happen if an exception is thrown. Multiple catches can be used to describe different types of Exceptions.
* - - `finally` this code is executed as long as the code is able to exit the try and catch block. It must be after the catch block but is *optional*.
* Words to be used outside of the class block are `import` and `package`. These will mostly be auto generated.
* `instanceof` is used to check the type of a variable.
* `new` is used in the context `new ObjectName(parameters)` to create new objects.
* Multithreading - `volatile` and `synchronized`. Don't worry about this.
* `native` - used for "native" language code. Don't worry about this.
* `const` and `goto` - literally do nothing.
* `return` causes the next statement to be the return value of the method.

These keywords may seem like alot of information so dont worry about it too much.
