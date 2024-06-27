# Python_Training_Exercise4

Below summary for what we learnt in this Seminar: With Advanced OOP

Class Method and Static Method in Python:
Class Method: A method that is bound to the class and not to any individual instance. It takes cls as the first parameter and can access class variables and methods. Defined with @classmethod decorator.
Static Method: A method that doesn't take a class or instance reference as the first parameter (self or cls). It's like a regular function within the class's namespace, used when access to neither class nor instance data is needed. Defined with @staticmethod decorator.
Encapsulating and Private, Protected Attributes:
Encapsulation: The practice of bundling data with methods that operate on that data, restricting direct access to some of the object's components, which is a fundamental principle of object-oriented programming.
Private Attributes: Attributes with a double underscore prefix (__attr), intended to be private to the class and inaccessible from outside. Python performs name mangling to achieve this.
Protected Attributes: Attributes with a single underscore prefix (_attr), indicating they are protected and intended for internal use by the class or subclasses, but accessible if necessary.
Property Decorators:
Property Decorators: Used to create managed attributes in a class. The @property decorator turns a method into a 'getter' for a property, allowing class attributes to be accessed like properties with additional logic if needed.
Setter/Deleter Decorators: In conjunction with @property, the @<property_name>.setter and @<property_name>.deleter decorators define corresponding setter and deleter methods, allowing for controlled assignment or removal of a property's value.

Multiple Inheritance:
Multiple Inheritance: A feature in some object-oriented programming languages where a class can inherit behaviors and characteristics from more than one parent class. This allows for more complex attribute and method composition.
Usage & Considerations: In Python, a class can inherit from multiple parent classes, which can introduce complexities like the diamond problem, resolved by the method resolution order (MRO). Careful design is needed to avoid conflicts.
Method Chaining:
Method Chaining: A coding style where multiple methods are called sequentially on the same object in a single line of code, with each call performing an operation and returning the object itself (self).
Fluent Interfaces: This pattern is often used to create fluent interfaces that allow for more readable and expressive code. It requires methods to return the instance (self) to enable the chaining of method calls.

