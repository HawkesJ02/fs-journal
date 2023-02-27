# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The entrypoint of applications varies. It can either be the homepage if there's not login or the login if that's the first thing the user sees. 
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A page is something that gets routed too and is well, a page. A component is like a subtemplate and controller that slots into the page. 
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
The V-for is the first one I can think of. Or slotting it to a compoenent and then using V-for, its very nice to quickly draw data.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
I had to look this one up but I believe its Component, slot and template. Which doesn't quite sound right but I will double check. 
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov substituation principle. This means that subclasses should extend the usefulness of the parent but don't break it from a client's point of view. 
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
The router-link comp. and also just router.js. Both are used to link tags, or at least this is how I've been doing it.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
Appstate is the bigger global object that many things reference. I can't quite remember what a state object is off the top of my head but my guess is its more limited to that component.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Its the same as it was before. Services manipulated the appstate data just like before with hardly any changes.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue. It seems to be the most important one. Although I'm looking into it now and am not quite sure about this.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
I have honestly no idea about the first but I know the style tag at the end of a component will limit itself to just that comp. I've used it a fair amount in the checkpoint. 
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
I looked this one up, I want to say hooks off the top of my head but the answer I got was well watchers. I'm struggling a bit more with vue than I thought so I will have to ask more about it.
```