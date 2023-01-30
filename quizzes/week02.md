# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Var and Let, the changable onces at least. Although I've never once used var.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A set of statements do perform task or calculate values, a mini (or long) set of instructions to do things. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility, Open Closed, Liskov sub, Interface and dependency aversion.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple should be at [2] because apple starts at [0].
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
This one is tricky so I will have to ask about it but as far as I am know I think it may be you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
If statements and else statement. If X is Y then do something and so on. If 5 + var = 8 then log success.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The Advancement, it lets the loop continue. For this one you could just put i++ 
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, when you render the dom the first file is the HTML file I believe. 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
From what I can tell:
Null, Undefined, Boolean, Number, BigInt, String, Symbol, Objects and maybe arrays. Though the last two I am not sure of.

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameter is used within the function, when declaring it and what it will do. Argument is used when calling the function and then slotted into it.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitives can never change they remain the same, true = true and false = false. Reference values can change and thus need to be referenced.
```