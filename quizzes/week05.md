# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
The letters in CRUD stand for C - Create, R - Read, U - Update, D - Delete.
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create maps to post, Read maps to get, Update maps to put and Delete maps to delete.
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM stands for object relational mapping. We use mongoose as an ORM when interacting with MongoDB.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
The two http requests that include a body are puts and posts
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
The first blank is synchronous, the second is asynchronous.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from 'mongoose'
Import . let Schema = mongoose.Schema;
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is software that exists between an operating system and the applications running on it.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Request and Response pipelines.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
http://https://www.google.com/search?q=tag+winter