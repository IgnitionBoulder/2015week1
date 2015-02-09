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
The role of HML is to be used to add elements into page such as hypertext, text, pictures, forms, and others.  

What is the role of CSS in a web page? 
CSS is either inline with a webpage or a separate document linked into a webpage that is used to style elements based on properties such as color, font types, margin sizes, and other properties.

What is the role of Javascript in a web page?  
JavaScript is used to add a dimension of interactivity within a web page, be that through a game, hover, animation, or even entire apps.

---

### Section 2: HTML and CSS 101

#### meta
Why do we separate HTML and CSS?  
We separate the two so that the pages aren't overly cluttered when editing code. We can easily move from one to the other and edit them easier than if we were to put all of the CSS in-line with the HML.

#### HTML
What are classes and IDs (and how are they different)?  
Classes can be used on multiple elements while IDs must contain unique values. IDs are declared in CSS documents using the "#" before the ID name while classes are defined with a "."

What are elements?  
Elements are what are found in between an opening and closing tag.

What are tags?  
Tags surround elements and give them meaning.

What are attributes?  
Attributes are extra information, usually found within an opening tag.

What are forms?  
Forms are used to collect input from users. From then, the form can manipulate the data according to how it's coded.

What is a div?  
Divs are placeholders in which users can add properties of CSS to chunks of information.

What are selectors?
Selectors are the CSS equivalents of tags, which surround properties to give them meaning. 

What are properties? 
Properties can be given values within selectors to modify a certain CSS styling.

What are values?  
Values are identifiers of properties which can be changed for a desired outcome.

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
There is a hierarchy of properties for every element, the more specific the selector, the higher precedence it takes. Also, the last selector of the same type will take precedence.

What are two CSS attributes you can change to push an element around on the page?  
You can change "right:" or "left:" in order to move around elements. I was confused by this question since I thought attributes were within HML tags.

What are the three different ways to include CSS in your project or use CSS to style a particular element? 
You can identify a font-type for everything within <p></p> tags, you can change the background color of every item in your list, or you can change the size of every one of your table elements to a percentage of the page.

---
### Section 3: Git and Github  
What is Git?  
Git is a distributed revision control system that has a repository with history of content with its content changes, that can be used fully collaboratively.

What is SCM?  
Source Code management is a way to check source code in and out of a repository.

What is a VCS?  
Version Control System, a system which takes different versions of a file and organizes them so you can see things like what changes were made. 

Why is Git useful for a developer?  
Git helps you edit and resave files.

Why is Git useful for a team of developers?  
Git combines different versions of revised files and shows who did what when and why.

How do you create a new Git repository for a project locally?  
git clone "source of repo"

How do you create it on Github?  
git remote add origin(or whatever else you want to call your remote repository) "repository URL"

How do you commit changes?  
git commit and you usually add a -m with a message in quotes afterwards so that you can leave a description of what was committed

What is the difference between staging and committing changes?  Staging is the predecessor to committing. When you stage, you prep for committing by grouping files together; and when you commit, you take a snapshot of the files at that current iteration.

What is the difference between committing your changes and pushing them to Github? 

Committing your changes only saves them to the current repo you're located in, usually locally, but pushing them to GitHub sends them to GitHub into your remote repository.

What is the command to check the status of your current repo in git?  
git status

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
git log
You can add tags such as -p or --stat to see which will tell you specific differences through each commit. You can also customize things such as commiter date and author email to show up.

How can you look through your historical commits on the Github website?  
You can navigate to the commits page of a repository or select an individual file and see its history.

What is a "Merge"?  
A merge is when you combine two branches back together that shared a parent.

What is a "Pull Request"? 
A pull request is a request to applying changes you've made to the master repository on GitHub, these do not have to be accepted, and can be discussed upon by the repository's author.

What is "Forking" a repo?  
Forking means you create a copy of a repo to make changes and then either return it with a pull request or use it as  a starting point to spin it off into your own version.

What is "Cloning" a repo?  
Cloning is used with a forked repo usually to edit the original repository's code on your local machine.

Android:
http://htmlpreview.github.io/?https://github.com/Victorrent/2015week1/blob/master/deliverables/android.html