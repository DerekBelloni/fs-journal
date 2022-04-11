# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace is used to declare a scope that contains a set of related objects.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
There are several differences between a class and a struct. A class is a reference type and a struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public is the access modifier of the Start() method
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
string is an indication of the data type.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract is preventing the creation of objects, they must be inherited
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
the virtual keyword modifies what proceeds it, such as a method, to be overridden by a derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected and default
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
private modifiers can only be accessed by code in the same class or struct in which it is declared.
```