# kottans-frontend :feet:

## Stage 0

### General

- [x] [Git Basics](#git-basics)
- [x] [Linux CLI and Networking](#linux-cli-and-networking)
- [x] [Git Collaboration](#git-collaboration)

### Front-End Basics

- [x] [Intro to HTML & CSS](#intro-to-html--css)
- [x] [Responsive Web Design](#responsive-web-design)
- [x] [HTML & CSS Practice](#html--css-practice)
- [x] [JavaScript Basics](#js-basics)
- [x] [Document Object Model](#dom) - practice

### Advanced Topics

- [x] [Building a Tiny JS World (pre-OOP)](#building-a-tiny-js-world) - practice
- [x] [Object-oriented JS](#object-oriented-javascript) - practice
- [x] [OOP exercise](#oop-exercise) - practice
- [ ] [Offline Web Applications](https://github.com/kottans/frontend/blob/master/tasks/app-design-offline.md)
- [x] [Memory pair game](#memory-pair-game) - real project!
- [ ] [Website Performance Optimization](https://github.com/kottans/frontend/blob/master/tasks/app-design-performance.md)
- [x] [Friends App](#friends-app) - real project!

---

### Git Basics

I knew some basic information about Git, but these lessons helped me to structure my knowledge.

:star: Course **Version Control with Git** completed. I've got a better understanding of a version control system and learned new helpful commands:

- git branch;
- git checkout;
- git add;
- git log --oneline;
- git log --oneline --graph --decorate --all;
- git commit --amend;
- git revert;
- git reset --soft and so on.

And their commit styleguide is worth using :arrow_right: <https://udacity.github.io/git-styleguide/>
![Udacity](/assets/udacity_git_course.jpg)

:star: **Main: Introduction Sequence, Remote: Push & Pull -- Git Remotes** (learngitbranching.js.org) completed. I've become aware of such commands as:

- git fetch;
- git rebase;
- git pull;
- git push and others.

![Main](/assets/learngitbranching_intro.jpg)
![Remote](/assets/learngitbranching_remote.jpg)

---

### Linux CLI and Networking

:star: **Linux Survival** (4 modules) - finished. I've learned new commands to work with directories and files:

- mkdir;
- ls;
- mv;
- cd;
- rm, rmdir and other.

I will definitely use some of them in future.

![Linux_Survival](/task_linux_cli/linux_sirvival.jpg)

:star: Articles **"HTTP: The Protocol Every Web Developer Must Know"** (part 1, 2) - read.
I knew some basic things and articles gave me extended information about HTTP, its methods and status codes. Also, I've learned about identification, authentication and caching.

---

### Git Collaboration

:star: Course **GitHub & Collaboration** completed. Now I know how to work with remote repositiories, fork them and keep track of team's work.

- git remote add - to add a connection to a new remote repository;
- git remote -v - to see the details about a connection to a remote;
- git shortlog;
- git log --grep - to specify commited information;
- git rebase -i `<base>` - to squash (combine) commits;
- git push -f - to force push the commits.

:fire: _You should not rebase if you have already pushed the commits you want to rebase. It's better to create a backup branch for rebasing!_

![Udacity](/task_git_collaboration/udacity_github_collaboration.jpg)

:star: **Main: Ramping Up, Moving Work Around, Remote: To Origin and Beyond** (learngitbranching.js.org) completed. The topics were quite challenging, but I managed to pass them and got new commands to use:

- git push `<remote> <place>` - to send commits from a local repository to a remote repository (where the commits _will come from_ and _where the commits will go_);
- git push origin `<source>:<destination>`;
- git fetch origin `<source>:<destination>`;
- git push origin :`<destination>` - for deleting branches;
- git fetch origin :`<destination>` - for creating branches;
- and others.

![Main](/task_git_collaboration/learngitbranching_main_ru_mwa.jpg)
![Remote](/task_git_collaboration/learngitbranching_remote_advanced.jpg)

:zap: Learning Git's commands, I structured my knowledge about version control system. Now it doesn't seem so confusing. I'm going to use these commands as much as possible. :zap:

---

### Intro to HTML and CSS

:star: Course **Intro to HTML & CSS (Eng)** finished. It suits complete beginners (there was nothing new for me). But it was good to refresh some basic points.

![Udacity](/task_html_css_intro/udacity_intro_html_css.jpg)

:star: Course **Learn HTML(Eng)** finished. It gave me solid understanding of how create different parts of the web page. It's good to use Semantic HTML that emphasizes the meaning of the encoded information over its presentation like:

- `<header>`;
- `<nav>`;
- `<main>`;
- `<footer>` and other.

![HTML](/task_html_css_intro/codecademy_html.jpg)

:star: Course **Learn CSS(Eng)** finished. I learned how to style and position HTML elements on the web page. The new information that I discovered was about CSS flexbox and its properties such as:

- `justify-content`;
- `flex-direction`;
- `align-content`;
- `align-items`;
- `flex-wrap` and so on.

Another powerful layout system is **CSS Grid** that can change both columns and rows. There must be a grid container (the one on which display: grid is applied) that is the direct parent of all the grid items and the children or grid items (i.e. _direct_ descendants) of the grid container. The propetries that are used for styling grid container and grid items are:

- `grid-template-columns / grid-template-rows` (width value can be either in pixels(px) or percentages(%));
- `grid-column-gap / grid-row-gap` - to determine the size of the gap between each row and each column;
- `grid-row-start / grid-row-end` - allow single grid items to take up multiple rows (also works for columns);
- `grid-row-gap / grid-column-gap` - to set the size of the gap between an element’s grid rows or columns;
- and others.

![CSS](/task_html_css_intro/codecademy_css.jpg)

---

### Responsive Web Design <a name="responsive-web-design"></a>

:star: Course **Responsive Web Design Fundamentals** completed. I refreshed some knowledge about media queries and I learned about patterns for responsive design:

- Column Drop;
- Mostly Fluid;
- Layout Shifter;
- Off Canvas.

:zap: The new thing for me is that it's better to start designing from the smallest viewport and then go bigger.

:bell: The other important thing: for small screens is to make tap-targets' size at least 48x48px.

![Responsive](/task_responsive_web_design/Udacity-responsive-web-design.jpg)

:star: **Flexbox Froggy** completed. It's quite interesting way to practice different properties of Flexbox such as:

- `justify-content` - to align elements horizontally;
- `align-items` - to align items vertically;
- `flex-direction` - to set the direction in which the elements will be positioned in the container;
- `order` - to change the places of the elements (it can have positive and negative values).

![Froggy](/task_responsive_web_design/flexbox-froggy.jpg)

:star: **Grid Garden** completed. I practiced using different properties of Grid:

- grid relative sizing unit `fr` - to split rows and/or columns into proportional distances;
- `grid-gap` property - a shorthand way of setting the two properties grid-row-gap and grid-column-gap;
- `grid-area` property specifies a grid item’s size and location in a grid layout and is a shorthand property for the `grid-row-start`, `grid-column-start`, `grid-row-end`, and `grid-column-end` in that order and other.

![GridGarden](/task_responsive_web_design/grid-garden.jpg)

---

### HTML & CSS Practice

:star: Hooli-style Popup finished. I found out how to create popup menu without JavaScript and learned how to use css properties like:

- `position: relative;`
- `position: absolute;`
- `z-index;`
- `overflow;`
- `:focus` state.

:arrow_down: Below you can find published web page and the code.

[Demo](https://shrai-dev.github.io/kottans-html-css-popup/) | [Code](https://github.com/Shrai-dev/kottans-html-css-popup)

---

### JS Basics

:star2: Course **Intro to JS** completed. It has tons of new information. This course helped me to broad my basic knowledge. And below there are some things not to forget: :arrow_down:

_The scope_ is defined as a specific portion of the code. There are three types of scope in Javascript:

_Global scope_ - When a particular variable is visible anywhere in the code. Such a variable is generally called as Global variable.

_Function scope_ - When a particular variable is visible within a particular function only. Such a variable is generally called as Local variable.

_Block scope_ - When a particular variable is visible within a pair of { . . . } only.

There are three ways _to declare a variable:_

`let` - It is a new way to declare a variable in any scope - Global, Local, or Block. The value of this variable can be changed or reassigned anytime within its scope.

`const` - It is also a way to declare constants in any scope - Global, Local, or Block. Once you are assigned a value to a const variable, the value of this variable CANNOT be changed or reassigned throughout the code.

`var` - This is the old way of declaring variables in only two scope - Global, or Local. Variables declared with the var keyword can not have Block Scope. The value of this variable can be changed or reassigned anytime within its scope.

:fire: _It is common to use uppercase variable identifiers for immutable values and lowercase or camelCase for mutable values (objects and arrays)._

_Parameters vs. Arguments_:
**A parameter** is always going to be a variable name and appears in the function declaration. On the other hand, **an argument** is always going to be a value (i.e. any of the JavaScript data types - a number, a string, a boolean, etc.) and will always appear in the code when the function is called or invoked.

_A function's return value can be stored in a variable or reused throughout your program as a function argument._

_Callbacks are the functions that are slipped or passed into another function to decide the invocation of that function._

**Objects** are one of the most important data structures in JavaScript. They have properties (information about the object) and methods (functions or capabilities the object has).

![Udacity](/task_js_basics/Udacity-intro-to-js.jpg)

:star2: **freeCodeCamp excercises** completed. They are interesting and easy at the beginning and becomes more challenging closer to the end.

_Basic JavaScript_ - really tiny exercises but have a lot of important information.

_ES6 Challenges_ - I've practiced the most recent standardized version of JS - ECMAScript 6 or ES6.

_Basic Data Structures_ - good excercises to learn how to manipulate arrays and objects.

_Basic Algorithm Scripting_ - very interesting exercises to train your brain.

_Functional Programming_ - I found out what it is about:

> Functional programming follows a few core principles:
>
> - Functions are independent from the state of the program or global variables. They only depend on >the arguments passed into them to make a calculation
> - Functions try to limit any changes to the state of the program and avoid changes to the global >objects holding data
> - Functions have minimal side effects in the program

:muscle: _Algorithm Scripting Challenges_ - it was the hardest part and took a lot of efforts to finally complete it.

![freeCodeCamp](/task_js_basics/freeCodeCamp_js.jpg)

---

### DOM

:star2: Course **JavaScript and the DOM** finished. I've learned a lot of new information that will help me to build interactive websites.

The DOM (stands for _"Document Object Model"_) is a model (representation) of the relationships and attributes of the HTML document that was received.

Some useful properties and methods:

- .innerHTML - to get an element's (and all of its descendants!) HTML content and set an element's HTML content;
- .textContent - to set the text content of an element (and all its descendants) and return the text content of an element (and all its descendants);
- .innerText - to get the visible text of the element;
- document.createElement() - to create an element;
- .appendChild() - to add an element as the last child of the parent element;
- setAttribute() - to set any attribute for an element;
- .classList - to access the list of classes;
- .toggle() - to add the class if it doesn't exists or remove it from the list if it does already exist;
- .contains() - returns a boolean based on if the class exists in the list or not.

![Udacity](/task_js_dom/Udacity_DOM.jpg)

:star2: **freecodecamp Algorithm Scripting Challenges** finished. The tasks were hard and really challenging.

![freeCodeCamp](/task_js_dom/freeCodeCamp.jpg)

:arrow_down: My version of interactive side-menu is below

[Demo](https://shrai-dev.github.io/kottans-interactive-side-menu/) | [Code](https://github.com/Shrai-dev/kottans-interactive-side-menu)

---

### Building a Tiny JS World

:star2: I've built a tiny JS world.

[Demo](https://shrai-dev.github.io/a-tiny-JS-world/)

---

### Object-Oriented JavaScript

:star2: Course **Object Oriented JS** completed. This topic is new to me. I've learned about prototypes and delegation and the word _this_:

- Concepts of lexical scope, execution context (in-memory scope), closures, prototype chains.
- The this keyword refers the calling object and can be used to access properties of the calling object.
- The value of this depends on where the this is being accessed from.
- The `__proto__` property is the property on every object that gives it access to the Object prototype property.

![Udacity](/task_js_oop/Udacity-1.jpg)
![Udacity](/task_js_oop/Udacity-2.jpg)

:arrow_down: Also, I made a Frogger Game.

[Demo](https://shrai-dev.github.io/frontend-nanodegree-arcade-game/) | [Code](https://github.com/Shrai-dev/frontend-nanodegree-arcade-game)

:star2: **Codewars**

I'd reached 6 kyu before this course.

My profile :arrow_right: [Anastasia](https://www.codewars.com/users/_Stacey_)

---

### OOP exercise

:star2: I've improved my Tiny JS World using Classes and all this information was completely new to me:

- classes specify the shared properties and methods that objects produced from the class will have.
- classes can have a **constructor** method. This is a special method that is called when the object is created (instantiated). Constructor methods are usually used to set initial values for the object.
- JavaScript classes support the concept of inheritance — a child class can _extend_ a parent class. This is accomplished by using the **extends** keyword as part of the class definition.
- A child class constructor calls the parent class constructor using the **super()** method.
- Every method is inherited just like properties.

:fire: The most controversial thing is that _Javascript does not have classes_. There have been many attempts to mimic classes in javascript, and there is even a Class in ES6, however, all these “replacements” are just syntactic sugar over the actual functionality that goes on under the hood.

[Demo](https://shrai-dev.github.io/a-tiny-JS-world/)

---

### Memory Pair Game

:tada: I have done a card game in which all of the cards are laid face down on a surface and two cards are flipped face up over each turn. The goal of the game is to turn over pairs of matching cards. The game ends when the last pair has been picked up.

It was an interesting experience to test all knowledge I gained and in the result got this simple game.

:arrow_down: Below you can find published game and the code.

[Demo](https://shrai-dev.github.io/memory-pair-game/) | [Code](https://github.com/Shrai-dev/memory-pair-game)

---

### Friends App

:tada: I have created a tiny social friends' search page with users cards, search, sorting and filtering of them by age, name and gender. It was a really difficult task for me: a lot of functions to implement but I learned how to use my knowledge and how create the whole task piece by piece.

:arrow_down: Below you can find published web page and the code.

[Demo](https://shrai-dev.github.io/friends-app/) | [Code](https://github.com/Shrai-dev/friends-app)
