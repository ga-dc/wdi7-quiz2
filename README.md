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
```In CSS, when an element is floated inside another element, the floated element may flow outside its parent container. The clearfix allows for the parent element to automatically clear its child elements. In class, we learned that it strategically places empty strings surrounding the floated element so that the parent container wraps around it nicely. The code for clearfix can be found online by googling. You place this in your CSS and call the clearfix class in your HTML for the element that you want to use it for.```    

### Question #2

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
[X] None of the above: Selects only li's that are direct children of all ul's of class "dropdown."
```

## Scope/Context/Closures

### Question #3

Describe the rules of scope in JavaScript.

Your Answer:
```There is global scope and local scope. It lets you know where a variable, object, or function is accessible. For example, global variables are accessible in all functions and objects throughout the document. Local variables are only accessible within their functions. If there are nested functions, local variables outside of the that scope will be accessible by functions inside. However, the innermost local variables would not be accessible outside of that scope. To make a local variable, you declare it with "var." Variables not declared with "var" will automatically be a global variable. Any variables, declared with var or not, outside of all functions and in the global scope will automatically be global variables.
```


### Question #4

Define an object and store it in a variable `pizza`. The object should have 2
properties: a temperature (set to 70), and a method called `bake`. When called,
this method should set the pizza's temperature to be 300. Note: you may not use
the variable pizza inside your method.

Your Answer:
```js
var pizza = {
  temperature: 70,
  bake: function () {
    this.temperature = 300;
  };   
}
```

## Callbacks

### Question #5

**Define a function called `doSomething`. It should take one argument, called
`thingToDo`. When called, `doSomething` should invoke the function given as an
argument. Finally, demonstrate calling `doSomething` with a function.**

Your Answer:
```js
function doSomething (thingToDo) {
  return 7 x thingToDo;

}

function thingToDo (a, b) {
  return a + b;
}
doSomething(thingToDo);
```

### Question #6

**What is the difference between synchronous and asynchronous program execution?**

Select all that apply:
```
[] Synchronous code runs at an even pace, asynchronous code runs with uneven pacing.
[] Synchronous code runs all at the same time, asynchronous code runs completely randomly
[X] Synchronous code runs in order (as appears in the source), asynchronous code may run at a later time.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

## jQuery

### Question #8

Which of the following statements will work, assuming jQuery is loaded?

Select all that apply:
```
[] `$(".post").css("background", "peachpuff")`
[] `$(".post").innerHTML`
[X] `$(".post").html()`
[X] `document.getElementsByClassName("post")[0].innerHTML`
[X] `document.getElementsByClassName("post").innerHTML`
```

### Question #9

Using jQuery, add an event listener for clicks on the button with the id
'greeting'. When the event happens, the code should append a paragraph to the
body, that says "hello".

Your Answer:
```js
$("button#greeting").on("click", function() {
  $("body").append("<p>hello</p>");
})
```

## Software Development Processes

### Question #10

Create a repo for project 1. (You don't need to fork, just create a brand new repo).

Create a readme.md in that repo. In the readme, write out five (5) user stories for your first project. Be sure to include a
role, goal, and reason for each.

Finally, link to your repo on github in the space below.

Your Answer:
```https://github.com/Ly900/Project-1-Memory-game
```
