# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Async happens outside the usual timeframe, it waits on other things. Sync happens normal like you'd expect (mostly), top down in a neatly fashion.

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
Its a observer pattern that looks around for changes to whatever its set, when a change occurs it does what is has been told to. Usually drawing something to the screen.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open closed principle. We should be able to add new things and lines of code without ruining the rest of the code.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is more or less what it sounds like, its a hoisted function (I believe) that stands out among the rest for importance and/or others to reference. 
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is from what I recall a message to be sent to the API, if the API sends it back then it gets fulfilled. I'm not 100% how to get the error but try catches have yet to let me down.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
I'm not 100% I have this one right but there's put, post, get.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
APPLICATION PROGRAMING INTERFACE. A fancy way to let two application or server or whatnot talk to each other.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Service models. The controller draws the data they get but since its handling data that's a service job.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Keep code where it should be, doing what it needs too without making a mess I suppose. But also for security, its harder to get into files you shouldn't be able too (in theory)

```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Sweet sweet, 200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Let me check the cats on this one, its INTERNAL SERVER ERROR. The cat has gotten in a broken the server. 
```