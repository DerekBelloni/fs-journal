# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
The keywords used to declare a variable in Javascript are var, let and const.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a set of statements that take an input and return an output where there is some relationship between the input and output.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The SOLID principles are S - Single Responsibility Principle, O - Open Closed Principle, L - Liskov Substitution Principle, I - Interface Segragation Principle, D - Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The index of pineapples current position in the fruit array is index 2. I know this because arrays are zero indexed, meaning the first position is index zero and I simply count up from
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
I would push objects from the 'them' array to 'you' array by using an array method, .push(). Specifically I would attach .push() to the 'you' array and then pass in them inside the push method, you.push(them).
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
An example of a Javascript conditional would be an 'if' statement where 'if' a certain condition or state of data exists then written code is told to execute.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The name of the piece that belongs in the blank spot in the for loop example above is the increment expression. To increase i by one every iteration, I would put i++ there.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The acronym 'DOM' stands for 'Document Object Model'. The first file accessed to render the 'DOM' is HTML.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The 9 ecmascript types defined by MDN for primitive values are Boolean, Null, Undefined, Number, BigInt, String, and Symbol. There are also Objects.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is part of a function declaration/definition and it defines what can be passed in as an argument when a function is invoked.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values can be thought of as granular or atomic (undividable) pieces of data and a reference value refers to objects that could be multiple pieces of data.
```