# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The three are encapsulation, inheritance and polymorphism. Abstraction may also be one of them but I am not fully sure about this.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
Hard to do without any intellisense but as far as I know it property.foreach(s => s.name)
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Breaking and dividing task into small groups so that they cannot be interfered with or interfere with each other. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle. Or making sure every function handles one task.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
The class is the like blueprint for what you want to make, the root value I suppose. An instance of a class is the built out thing with all the values and whatnots. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxy is like a clone of the object. Not the real object but referencing it so it can be used but  also remain safe locked away from prying eyes. 

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Encapsulates things that need to be. Only lets the user control what needs to be controlled and also helps with organization.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes in user inputs and relays it to the service. Then updates the DOM accordingly and all the things that the user can see on the screen.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service takes in the appdate and uses this to run functions. Maths and data management happen here that the controller shouldn't directly be linked too. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model contructs the data to the screen. Holds templates to be drawn later and otherwise the blueprint areas of what you are trying to accomplish. 
```
