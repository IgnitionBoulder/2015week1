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
The "skeleton" of the page

What is the role of CSS in a web page?  
The "skin" that goes over the HTML skeleton

What is the role of Javascript in a web page?  
Mainly Client-side behavior that HTML and CSS is incapable of
---

### Section 2: HTML and CSS 101

#### meta
Why do we separate HTML and CSS?  
Stylistic reasons mainly; effciency when coding

#### HTML
What are classes and IDs (and how are they different)?  
ID's are unique in the sense that there can be only one ID per elememnt per page. Classes are not unique are many elements can have the same class and many classes can have the same element

What are elements?  
Elements are basically the content between tags

What are tags? 
Tags always have a start and end. Ex: <p ></p > or <ol ></ol > etc. etc. (Note: spaces in tags are there so they will not disappear)

What are attributes?  
Always specified in the start tag; basically anything that is followed with an =" ". Ex: src=, alt=, href=, etc. etc.

What are forms? 
A type of tag; used to collect information/user input

What is a div?  
A type of tag; defines a division or a section in an HTML document; importantly compabitable with CSS to format pages

What are selectors?  
Classes and ID's are examples of selectors; in CSS selectors are patterns used to select used to select element(s) you want to style

What are properties?  
There are tons and tons of properties; change how the code is represented; ex: font-family, font-size, color, border, etc.

What are values?  
Values are what follow properties such as color exmaples, font exmaples, sizes; paired with attributes

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles? 
Front its parent. Some styles (such as family-font, text-alignment, etc.) are automatically inherited by child elements from their parent element (i.e. by an element contained inside another one).

What are two CSS attributes you can change to push an element around on the page?  
id and and class

What are the three different ways to include CSS in your project or use CSS to style a particular element?  
Borders (border-collpase, border sizes, etc.), tables (td, th, width, height, etc.), links (a:link, a:visited, a:hover, etc.), background colors - there are many more. 

---
### Section 3: Git and Github  
What is Git?  
A control system software for software development that contains repositories.  

What is SCM?  
Software configuration management: tracking and controlling changes in the software

What is a VCS?  
Version control server: what Git is practically.

Why is Git useful for a developer?  
Local branching, convenient staging areas, and multiple workflows to name a few reasons.

Why is Git useful for a team of developers?  
Through merging, forking, pulling, and commiting changes to repos one can work locally and then share, create, and commit efforts onto the master branch.

How do you create a new Git repository for a project locally?  
Using the command line:
$ git init
$ git add .
$ commit -m "First commit"
Then on github find the remote respository URL
$ git remote add origin -insert URL-
$ git remote -v
$ git push origin master


How do you create it on Github?  
In the upper right hand corner there is a + sign with dropdown options - adding a repo is located there

How do you commit changes?  
At the bottom of the repo there is a commit changes button - you can also make comments to your updates

What is the difference between staging and committing changes? 
There is a working directory and staging area between you and the repository. You can stage fixes by doing work in the directory and staging the work before actually making a commit to the repository.

What is the difference between committing your changes and pushing them to Github?  
Commiting is like hitting save on Github where as pushing refers to sending your committed changes to a remote repository on a site such as Github

What is the command to check the status of your current repo in git?  
$ git status

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
$ git log
You can limit your searches in many ways, especially by time.
You can also format your log output.

How can you look through your historical commits on the Github website?  
The history tab - shows a detailed log of all of your previous commits

What is a "Merge"?  
Takes the changes from one branch and applies them into another. This often happens as a pull request.

What is a "Pull Request"?  
Proposed changes to a repo that can be accepted or rejected once submitted 

What is "Forking" a repo?  
What is "Cloning" a repo?  
