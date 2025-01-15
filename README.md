# C# Direct Field Access Example

This repository demonstrates a potential issue with direct field access in C# classes.  While it's technically possible to access private fields directly from within the class, it's generally considered bad practice because it undermines encapsulation and can make code harder to maintain and refactor.  The example shows a simple class with a property and field; the solution shows how to improve the code by consistently using the property.

## Bug
The `bug.cs` file shows the class using a combination of property access and direct field access. Direct access reduces maintainability.