# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
1) Var
2) Let
3) Const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A piece of code that you can call at any time that enacts a special job.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
1) Single responsibility: A class should only have on responsibility and no more, no less.
2) Open Closed principle: A class should be open for extension, but not for modifications
3) Liskov Substitution: Objects in a program should be interchangeable with other types of itself without changing the way the program works.
4) Interface Segregation: Separate the interfaces based on the requisites of the program, rather than one general interface
5) Dependency Inversion: the page should depend on abnormalities instead on concrete situations
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
fruit[2] = pineapple
essentially pineapple is located at index level 2
that is the case because an array starts 0 and goes up, and since it is the third element and it starts from 0, 0->1->(2)
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```js
let your_friends = you.friends
your_friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
1) if () {}
2) else {}
3) else if () {}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
1) the Increment or Decrement
2) i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
1) Document Object Model
2) .HTML file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
1) boolean
2) null
3) undefined
4) number
5) bigint
6) string
7) symbol
8) object
9) array / list
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
1) The parameter is the item that is inside the function and can directly be used and manipulated by the function to provide it's service.
2) The Argument is the item provided to the function by the line and it is called at.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
1) A Primitive value, in storage, is directly stored as what it's value is.
2) A Reference value, in storage, has the location of the value of the item to find it, but not the value itself.
```