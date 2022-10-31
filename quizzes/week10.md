# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
to have the classes for controllers, services, etc. be structured together and allow certain files to use certain ones
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
same as class but has default public on its functions
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the type of data returned
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
makes the class have to be inherited
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
allows children classes to modify the method
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
private
internal
protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
itself only
```