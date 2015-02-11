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
HTML is the skeleton of a webpage--we use HTML to write the most basic outline of the elements.

What is the role of CSS in a web page?  
CSS is the hair and makeup of a web page in that it makes the functionalities pretty and contributes to user friendliness.

What is the role of Javascript in a web page?  
Javascript tracks user interactions in the web page, useful for companies and developers to expand menus, change the layout, and make the website more interactive with user input. It controls events by the user.

---

### Section 2: HTML and CSS 101

#### Meta
Why do we separate HTML and CSS?  
You can apply formatting to several HTML elements without having to rewrite the code and you can apply similar formatting to multiple HTML pages from a single CSS file. Separating also makes the code more readable by way of cleaving the two functionalities that HTML and CSS serve.

#### HTML
What are classes and IDs (and how are they different)?  
Classes allow you to style a collection of objects that are all labeled within the same class. IDs classify an individual object, whereas classes identify a collection of objects.

What are elements?  
Elements are anything included between tags. 

What are tags?
Tags are deliminators which give structure to the different sections of the web page, like the way an essay is separated into paragraphs. Tags creates sections of content. They should have an open and a close, and can be embedded within one another.

What are attributes? 
An attribute is a characteristic or description for some content in the element. They give tags more instructions, for instance changing the color or size of some text.

What are forms? 
Forms are HTML elements used to collect user input, mainly for different kinds of buttons.

What is a div?
A div element groups other elements together into sections of the web page, such as a navigation bar, the main body, and the footer. It divides the page into "divided containers".

#### CSS
What are selectors?  
A selector is the HTML element that you are going to manipulate.

What are properties? 
A property is an aspect of the selector, such as font-style and color. You can set multiple properties for one selector.

What are values? 
A value is a possible setting for a property, like "Verdana" is a value for the "font-type" property.

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?
A element contained inside the selector inherits all styles given to that selector unless specifically overidden.

What are two CSS attributes you can change to push an element around on the page?  
Position could be static, fixed, relative, absolute, floating.

What are the three different ways to include CSS in your project or use CSS to style a particular element?  
First, in my HTML file I could link to a .css file which contains all my styling. Second, I could put my CSS changes in the style tags under the head of my HTML file. For minor and specific changes, I could add changes within an HTML tag using the style keyword.

#### Android
Put your html code in the `android.html` file in this folder.

---
### Section 3: Git and Github  
What is Git?  
Git is a VCS which stores and tracks code changes and keeps versions. 

What is SCM? 
Software configuration management; the tracking and controlling of changes in software.  

What is a VCS?  
Version control system which handles the goals of an SCM by creating a framework to track software changes and versions. 

Why is Git useful for a developer?  
It allows a developer to update code while being able to keep revisions and changes incase code breaks in the future.

Why is Git useful for a team of developers?  
Teams can track other member's changes as well as be notified when there are changes in code.Teams can also work on different branches and merge to centralized source code.

How do you create a new Git repository for a project locally?  
git init (name)

How do you create it on Github?  
click on the new repository button and name the repo.

How do you commit changes?  
git commit -m "commit message here"

What is the difference between staging and committing changes? 
Staging indexes all the files to be committed to git, while actually committing sends them to the local repo.  

What is the difference between committing your changes and pushing them to Github? 
Committing changes adds the to your local repository while pushing them adds them to the remote respository.

What is the command to check the status of your current repo in git? 
git status 

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
git log. You can add a -p flag to view the differences between changes and you can use a -(int) flag to only allow int number of the last entries. --pretty makes the output more readable.

How can you look through your historical commits on the Github website?  
On the repo page, click the commit tab at the top. This shows all previous commits and their unique identifier.

What is a "Merge"? 
Merges a branch of code changes to the main github repo. 

What is a "Pull Request"?
Notifies the user in charge of the repo that you've made changes to his/her code, shows these changes, and allows the person in charge to accept or reject these changes.

What is "Forking" a repo?  
"forking" a repo on the server side. This means that you can easily contribute to the upstream (main) part of the repo by merging. The remote is saved for you.

What is "Cloning" a repo?  
Cloning copies a repo's files to your local machine, but doesn't allow you to push changes to the code unless you are marked as a contributor on a repo.
