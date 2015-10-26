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
A CSS clearfix is used to fix issues related to floating child elements within a parent element
```
Normally we would do this
<div>
    <div style="float: left;">Sidebar</div>
    <div style="clear: both;"></div>
</div>
With Cleatfix we need only
<div class="clearfix">
    <div style="float: left;" class="clearfix">Sidebar</div>
</div>
.clearfix:after {
  content: "";
  display: table;
  clear: both;
}

### Question #2

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[+] Selects all li's which are directly inside a ul of class dropdown (children)

```

## Scope/Context/Closures

### Question #3

Describe the rules of scope in JavaScript.

Your Answer:
1. A variable that is declared outside a function definition is a global variable, and its value is accessible and modifiable throughout your program.
2. A variable that is declared inside a function definition is local. It is created and destroyed every time the function is executed, and it can not be accessed by any code outside the function.
```


### Question #4

Define an object and store it in a variable `pizza`. The object should have 2
properties: a temperature (set to 70), and a method called `bake`. When called,
this method should set the pizza's temperature to be 300. Note: you may not use
the variable pizza inside your method.

Your Answer:
```js
// write code here
```

## Callbacks

### Question #5

**Define a function called `doSomething`. It should take one argument, called
`thingToDo`. When called, `doSomething` should invoke the function given as an
argument. Finally, demonstrate calling `doSomething` with a function.**

Your Answer:
```js
// write code here
```

### Question #6

**What is the difference between synchronous and asynchronous program execution?**

Select all that apply:
```
[+] Synchronous code runs in order (as appears in the source), asynchronous code may run at a later time.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[+] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request

## jQuery

### Question #8

Which of the following statements will work, assuming jQuery is loaded?

Select all that apply:
```
[+] `$(".post").css("background", "peachpuff")`
[+] `$(".post").html()`


### Question #9

Using jQuery, add an event listener for clicks on the button with the id
'greeting'. When the event happens, the code should append a paragraph to the
body, that says "hello".

Your Answer:
```js
$(document).ready(function() {
  $('#greeting').click(function){
  $('p').append('hello');
});
});

## Software Development Processes

### Question #10

Create a repo for project 1. (You don''t need to fork, just create a brand new repo).

Create a readme.md in that repo. In the readme, write out five (5) user stories for your first project. Be sure to include a
role, goal, and reason for each.

Finally, link to your repo on github in the space below.

Your Answer:
https://github.com/mkotylevska/Project_1.git
