# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace is used to declare scope.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct is more similar to a simple data value and a class is a dynamic object.
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
Virtual
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
string indicates what will be return from the function.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
When using abstract you cannot create an object.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
This allows for derived classes to override this function if need be.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, and internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
This limits the accessability to the function or class. 
```