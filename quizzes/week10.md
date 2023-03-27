# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces are areas that you store the nanes of codes and prevent problems with naming. Organization of names so they don't interfere.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structures are values types. Classes are refrence types.`
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
I will have to look at this one but I believe it is a refrence. It may be a pointer but I'm not 100% sure about this.

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
It runs the function. In this case it will make a virtual and input the word vroom.

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
Type of data, a word, characters. This one is Vroom
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It cannot be used to create an object. It just accesses the data I believe.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Its like putting on object on an object. Its an object that is tacked onto another for refrence. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, protected, default, private. Default is baseline.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Whatever is trying toaccess it can only do so in its own class. It cannot be accessed outside the class. 
```