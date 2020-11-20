# kottans-frontend

## Stage 0

### General
* [x] [Git Basics](#git-basics)
* [x] [Linux CLI and Networking](https://github.com/kottans/frontend/blob/master/tasks/linux-cli-http.md)
* [x] [VCS (hello gitty), GitHub and Collaboration](https://github.com/kottans/frontend/blob/master/tasks/git-collaboration.md)

### Front-End Basics
* [x] [Intro to HTML & CSS](https://github.com/kottans/frontend/blob/master/tasks/html-css-intro.md)
* [x] [Responsive Web Design](#responsive-web-design)
* [ ] [HTML & CSS Practice](https://github.com/kottans/frontend/blob/master/tasks/html-css-popup.md)
* [ ] [JavaScript Basics](https://github.com/kottans/frontend/blob/master/tasks/js-basics.md)
* [ ] [Document Object Model](https://github.com/kottans/frontend/blob/master/tasks/js-dom.md) - practice

### Advanced Topics
* [ ] [Building a Tiny JS World (pre-OOP)](https://github.com/kottans/frontend/blob/master/tasks/js-pre-oop.md) - practice
* [ ] [Object oriented JS](https://github.com/kottans/frontend/blob/master/tasks/js-oop.md) - practice
* [ ] [OOP exercise](https://github.com/kottans/frontend/blob/master/tasks/js-post-oop.md) - practice
* [ ] [Offline Web Applications](https://github.com/kottans/frontend/blob/master/tasks/app-design-offline.md)
* [ ] [Memory pair game](https://github.com/kottans/frontend/blob/master/tasks/memory-pair-game.md) - real project!
* [ ] [Website Performance Optimization](https://github.com/kottans/frontend/blob/master/tasks/app-design-performance.md)
* [ ] [Friends App](https://github.com/kottans/frontend/blob/master/tasks/friends-app.md) - real project!
-----
### Git Basics
I knew some basic information about Git, but these lessons helped me to structure my knowledge.

:star: Course **Version Control with Git** completed. I've got a better understanding of a version control system and learned new helpful commands:
  + git branch;
  + git checkout;
  + git add;
  + git log --oneline;
  + git log --oneline --graph --decorate --all;
  + git commit --amend;
  + git revert;
  + git reset --soft and so on.

And their commit styleguide is worth using :arrow_right: <https://udacity.github.io/git-styleguide/>
![Udacity](/assets/udacity_git_course.jpg)

:star: **Main: Introduction Sequence, Remote: Push & Pull -- Git Remotes** (learngitbranching.js.org) completed. I've become aware of such commands as:
  + git fetch;
  + git rebase;
  + git pull;
  + git push and others.
  
![Main](/assets/learngitbranching_intro.jpg)
![Remote](/assets/learngitbranching_remote.jpg)
-----
### Linux CLI, and HTTP

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

-----
### Git Collaboration
:star: Course **GitHub & Collaboration** completed. Now I know how to work with remote repositiories, fork them and keep track of team's work.

  + git remote add - to add a connection to a new remote repository;
  + git remote -v - to see the details about a connection to a remote;
  + git shortlog;
  + git log --grep - to specify commited information;
  + git rebase -i `<base>` - to squash (combine) commits;
  + git push -f - to force push the commits.

:fire: *You should not rebase if you have already pushed the commits you want to rebase. It's better to create a backup branch for rebasing!*

![Udacity](/task_git_collaboration/udacity_github_collaboration.jpg)

:star: **Main: Ramping Up, Moving Work Around, Remote: To Origin and Beyond** (learngitbranching.js.org) completed. The topics were quite challenging, but I managed to pass them and got new commands to use:
  - git push `<remote> <place>` - to send commits from a local repository to a remote repository (where the commits *will come from* and *where the commits will go*);
  - git push origin `<source>:<destination>`;
  - git fetch origin `<source>:<destination>`;
  - git push origin :`<destination>` - for deleting branches;
  - git fetch origin :`<destination>` - for creating branches;
  - and others.

![Main](/task_git_collaboration/learngitbranching_main_ru_mwa.jpg)
![Remote](/task_git_collaboration/learngitbranching_remote_advanced.jpg)

:zap: Learning Git's commands, I structured my knowledge about version control system. Now it doesn't seem so confusing. I'm going to use these commands as much as possible. :zap:

-----
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
  + justify-content;
  + flex-direction;
  + align-content;
  + align-items;
  + flex-wrap and so on.

Another powerful layout system is **CSS Grid** that can change both columns and rows. There must be a grid container (the one on which display: grid is applied) that is the direct parent of all the grid items and the children or grid items (i.e. *direct* descendants) of the grid container. The propetries that are used for styling grid container and grid items are:
  - grid-template-columns / grid-template-rows (width value can be either in pixels(px) or percentages(%));
  - grid-column-gap / grid-row-gap - to determine the size of the gap between each row and each column;
  - grid-row-start / grid-row-end - allow single grid items to take up multiple rows (also works for columns);
  - grid-row-gap / grid-column-gap - to set the size of the gap between an element’s grid rows or columns;
  - and others.

![CSS](/task_html_css_intro/codecademy_css.jpg)

### Responsive Web Design <a name="responsive-web-design"></a>

:star: Course **Responsive Web Design Fundamentals** completed. I refreshed some knowledge about media queries and I learned about patterns for responsive design:
  + Column Drop;
  + Mostly Fluid;
  + Layout Shifter;
  + Off Canvas.

:zap: The new thing for me is that it's better to start designing from the smallest viewport and then go bigger.

:bell: The other important thing for small screens is to make tap-targets' size at least 48x48px.

![Responsive](/task_responsive_web_design/Udacity-responsive-web-design.jpg)

:star: **Flexbox Froggy** completed. It's quite interesting way to practice different properties of Flexbox such as:
  + justify-content - to align elements horizontally;
  + align-items - to align items vertically;
  + flex-direction - to set the direction in which the elements will be positioned in the container;
  + order - to change the places of the elements (it can have positive and negative values).

![Froggy](/task_responsive_web_design/flexbox-froggy.jpg)

:arrow_down: to be continued..
