# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CREATE, READ, UPDATE, and DELETE
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
POST, GET, PUT, and DELETE

```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Mapper. We use Node.js I believe when using MongDb
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
PUT and POST since your sending new data up in each function. The other two read or just destroy data.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
As far as I can tell the first is a sync coding model and the second is look for async. 
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import schema from (moongoose), let schema = name.schema 
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Software that applications use to communicate with each other. An API I believe would be a great example of this. 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
I honestly am drawing a blank on what the fill in on these blanks. I will have to ask because I have honestly no clue. 
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
it would look something like: https://baseurl?tag=winter

```