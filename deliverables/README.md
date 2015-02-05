# Week 1 Deliverable  

### Instructions  

In order to deliver homework consisting of questions and answers, just edit this file and commit the changes.  Once your answers are on Github, specifically in this file, you have delivered your homework.  
  
To answer questions, please just put the answer on the next line after the question.  Put a blank line after the answer to separate it visually from the next question.  

Example:  

**What is your name?**  
Sir Student of Ruby

**What is your quest?**
I seek the Rails  

**What is your favorite color?**
~~Green~~ edit:  No, blue.  Blue!  

For projects on Code Academy, or other external exercises, please just paste a link into your deliverables file where we can see the result.  

### Section 1: The Front End
#### Required - Answer these questions in the deliverables file, and complete the following. 
What is the role of HTML in a web page?  
  The skeleton of a WP (web page)

What is the role of CSS in a web page?
Allows designers to have more control and creativity over WP

What is the role of Javascript in a web page?  
  Used for interactive and dynamic display of webpage

---

### Section 2: HTML and CSS 101

#### Meta
Why do we separate HTML and CSS?  
  You choose: easier editing, readability, cachability, reduces page load time, etc...

#### HTML
What are classes and IDs (and how are they different)?  
  ID is **Unique**: Each element can only have one ID and each page can only have one element w/ that ID.  Classes are 
slutty: they can be used multiple times on multiple types of elements on the same page.

What are elements?  
  Individual components on a webpage: IE a singe < p >Blah Blah< /p >

What are tags?  
  < p > or < title > etc...

What are attributes?  
  Attach extra information to an element

What are forms?  
  Used to collect user information from a webpage

What is a div?
AKA Division: element that divides a webpage (usually element gets it's own line)

#### CSS
What are selectors?  
  p { Blah } -> the p is the selector, allows developer to choose elements to change

What are properties?  
  .... -_- .... attributes of elements that you can change in CSS -> font-size, color, etc...

What are values?  
  specific property values -> color:red or color:green. 

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
  Through nesting elements of trees.  Recieved from parent elements.

What are two CSS attributes you can change to push an element around on the page?  
  Float or Margin

What are the three different ways to include CSS in your project or use CSS to style a particular element?
  Inlined, linked or embeded

#### Android
Put your html code in the `android.html` file in this folder. 

---
### Section 3: Git and Github  
What is Git?  
  A version control system for projects

What is SCM?  
  Supply Chain Management

What is a VCS?  
  Veritas Cluster Server? The cluster software for Linux...?

Why is Git useful for a developer?  
  Easily tracks and controls changes to a project

Why is Git useful for a team of developers?  
  Exact same reason and your able to fork and clone project for multiple developers

How do you create a new Git repository for a project locally?  
  git init

How do you create it on Github?  
  Uhhh click the 'new repository' button

How do you commit changes?  
  git commit

What is the difference between staging and committing changes?  
  Commiting changes the repository file, staging is essntially a temp file for working changes before commiting.

What is the difference between committing your changes and pushing them to Github?  
  Commiting changes the repository file, pushing updates remote reference files AKA: your website/application

What is the command to check the status of your current repo in git?  
  git status

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?
  git log, git log --stat, git log -p  -> had to look up the variations

How can you look through your historical commits on the Github website?
  Use the history option/tab

What is a "Merge"?  
  Joins multiple files/development histories

What is a "Pull Request"?  
  Shows changes made to a repository

What is "Forking" a repo?  
  Creates a new repository of a [piece of a] project for each user yet relates back to original project.

What is "Cloning" a repo?  
  Creates a full new [piece of a] project that does not allow one to commit changes to original project.
