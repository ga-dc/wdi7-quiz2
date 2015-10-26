# Quiz #2

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## CSS

### Question #1

Describe the purpose of a clearfix in CSS, and give an example of how to do it.

Your Answer:
```Clearfix is used to make a div expand to enclose all of it's floating child elements

<div class='clearfix'>
    <div style='float: right;' class='clearfix'>some element</div>
    </div>
```

### Question #2

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[x] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

## Scope/Context/Closures

### Question #3

Describe the rules of scope in JavaScript.

Your Answer:
```Scope is how JS understands how it can use variables. Global scope would be a variable defined outside of a function. These variable scan be used in multiple functions. Local scope is a variable defined inside a function. That variable can only be used in that function and any nested functions.
```


### Question #4

Define an object and store it in a variable `pizza`. The object should have 2
properties: a temperature (set to 70), and a method called `bake`. When called,
this method should set the pizza's temperature to be 300. Note: you may not use
the variable pizza inside your method.

Your Answer:
```js
// var pizza = {type:'pepperoni', temp:70}
    // pizzaBake: function bake() {
    //   this.temp.replaceChild('70', '300');  
    // }
```

## Callbacks

### Question #5

**Define a function called `doSomething`. It should take one argument, called
`thingToDo`. When called, `doSomething` should invoke the function given as an
argument. Finally, demonstrate calling `doSomething` with a function.**

Your Answer:
```js
//function doSomething(thingToDo){
//     return thingToDo();
// }
//     function thingToDo(){
//       alert('somethingDone')
//     }

```

### Question #6

**What is the difference between synchronous and asynchronous program execution?**

Select all that apply:
```
[x] Synchronous code runs at an even pace, asynchronous code runs with uneven pacing.
[] Synchronous code runs all at the same time, asynchronous code runs completely randomly
[x] Synchronous code runs in order (as appears in the source), asynchronous code may run at a later time.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[x] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

## jQuery

### Question #8

Which of the following statements will work, assuming jQuery is loaded?

Select all that apply:
```
[x] `$(".post").css("background", "peachpuff")`
[x] `$(".post").innerHTML`
[x] `$(".post").html()`
[] `document.getElementsByClassName("post")[0].innerHTML`
[] `document.getElementsByClassName("post").innerHTML`
```

### Question #9

Using jQuery, add an event listener for clicks on the button with the id
'greeting'. When the event happens, the code should append a paragraph to the
body, that says "hello".

Your Answer:
```js
// $('#greeting').click(function) {
  //   $('body').append(document.createTextNode('<p>Hey There!</p>')
  // );
  // }
```

## Software Development Processes

### Question #10

Create a repo for project 1. (You don't need to fork, just create a brand new repo).

Create a readme.md in that repo. In the readme, write out five (5) user stories for your first project. Be sure to include a
role, goal, and reason for each.

Finally, link to your repo on github in the space below.

Your Answer:
```https://github.com/ArmaniH/Project-1
```
