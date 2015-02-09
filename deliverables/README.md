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
HTML defines the structure of a web page.

What is the role of CSS in a web page?  
CSS defines the presentation of a web page.

What is the role of Javascript in a web page?  
Javascript provides interactivity within a web page.
---

### Section 2: HTML and CSS 101

#### meta
Why do we separate HTML and CSS?  
Abstracting CSS from the HTML is a best practice that makes the HTML  
easier to read, and therefore easier to debug/change.

#### HTML
What are classes and IDs (and how are they different)?  
Classes are CSS selectors for identifying multiple elements whereas IDs identify a single element.

What are elements?  
Elements are basic components that a web page is made of.

What are tags?  
Tags define the beginning and end of an element.

What are attributes?  
Attributes modify/specify behavior of elements.

What are forms?  
Forms define user input areas to be sent to the webserver.

What is a div?  
A div is a "division" HTML element whose purpose is to divide a web page.



What are selectors?  
CSS selectors identify a collection of properties to apply to a certain element.

What are properties?  
Properties define display of an element based on it's associated value.

What are values?  
Values specify the interpretation of a CSS selector's property. 

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
Elements inherit their default style from their parent element, otherwise they get them from the CSS selector  
that's applied to them.

What are two CSS attributes you can change to push an element around on the page?  
Float and top/left

What are the three different ways to include CSS in your project or use CSS to style a particular element?  
- include from file with <link rel="stylesheet" href="/path/to/stylesheet">
- inline in the tag with the style attribute like <p style="color: red;">asdf</p>
- between <style></style> tags

---
### Section 3: Git and Github  
What is Git?  
Git is a piece of version control software used for managing a code base.

What is SCM?  
An SCM is either
	- Source Control Management: just the software involved with versioning and revisions in a codebase, like git
	- Software Configuration Management: software package involving versioning, distribution, dependencies, etc

What is a VCS?  
Version control software, a tool to manage revisions and backups of a codebase.

Why is Git useful for a developer?  
It allows developers to both track progress and revert bad changes easily, as well as  
compartmentalization of new features  

Why is Git useful for a team of developers?  
The development cycle and features can be tracked easier with git, and one can isolate different
sections of a project with branches similar to if it were just a single developer. 

How do you create a new Git repository for a project locally?  
git init

How do you create it on Github?  
Click new repository > enter repo name and description 

How do you commit changes?  
1. First add files to commit with git add <files>  
2. commit the changes with git commit -m "commit message goes here"  

What is the difference between staging and committing changes?  
"git add" stages files for a commit, "git commit" creates a new commit that 'saves' the staged files  

What is the difference between committing your changes and pushing them to Github?  
committing saves the changes locally, pushing uploads the code to the remote repository (in this case github)  

What is the command to check the status of your current repo in git?  
git status  

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
git log  
 -n <#> : limits commits displayed to the # given  
 -until=<date> : shows commits older than date  
 -since=<date> : shows commmits newer than date  
 -author=<pattern> : matches regex pattern with commit author  

How can you look through your historical commits on the Github website?  
click the "<#> commits" button that says how many commits the repo has, it's below  
the repo description

What is a "Merge"?  
a merge is combining two different versions of a codebase/files in a codebase  

What is a "Pull Request"?  
a pull request is a request to a repository to have one's changes pulled into the main codebase  

What is "Forking" a repo?  
forking is copying a repo into one's own account  

What is "Cloning" a repo?  
cloning a repo is copying a repo from a remote repository to a local version  


Android Assignment  
http://htmlpreview.github.io/?https://github.com/SimonRuppGreene/2015week1/blob/master/deliverables/android.html