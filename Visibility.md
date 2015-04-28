#Visibility

I think visibility is important enough to deserve a summary of its own.

* `private` - this signifies that this component, is only visible in the current file you are working on.
_Example:_ `private int ammountOfCash;` - this tells Java that the _**only** things_ that can directly use the variable ammountOfCash are in the same file as this variable.

* - not having a visibility is also a visibility! It is called the default visibility. This is the least used, ironically. We won't utilize it but it will only allow things in the direct package the code is made to use it. You will learn what a package is below.

* `protected` - allows the same visibility given by the default visibility but also allows the subclasses and their packages to access the component.

* `public` - this allows anything that has a reference to this object to call it.
