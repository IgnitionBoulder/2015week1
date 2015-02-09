# Week 1 Deliverable  

### Instructions  

In order to deliver homework consisting of questions and answers, just edit this file and commit the changes.  Once your answers are on Github, specifically in this file, you have delivered your homework.  
  
To answer questions, please just put the answer on the next line after the question.  Put a blank line after the answer to separate it visually from the next question.  

Example:  

**What is your name?**    
Erin Connolly

**What is your quest?**  
They say not to leave home without a map, but I usually do. 

**What is your favorite color?**  
Green, if it's with tangerine and sky blue 

For projects on Code Academy, or other external exercises, please just paste a link into your deliverables file where we can see the result.  

### Section 1: The Front End
#### Required - Answer these questions in the deliverables file, and complete the following. 
What is the role of HTML in a web page?  
The skeleton that gives every webpage structure.  Used to add things like paragraphs, headings, links, pictures, tables, etc. 
What is the role of CSS in a web page? 
Contains all the style elements and how they apply to the HTML elements, provides the appearance

What is the role of Javascript in a web page?   
Primarily to allow for interactions of the users with the code

---

### Section 2: HTML and CSS 101

#### meta
Why do we separate HTML and CSS?

More efficiency.  If style tags had to applied to every single HTML element, designing a website would be much more tedious.  For example  
each line of HTML in a list that should have the same style would need the same style tags repeated.  With a separate branch of code,   
CSS, we can apply design code to types and classes of elements, thereby reducing the volume of code.  Additionally, most maintain that you  
should separate your HTML and CSS code.  The main advantage of this practice is that: (1) it allows you to apply CSS to other HTML and visa versa  
(2)prevents spaghetti code when scaling up and introducing more complexity and lenght to your projects.

#### HTML
What are classes and IDs (and how are they different)?  
Classes are CSS selectors, along with the universal selector and HTML elements.  Classes can be used to indicate multiple elements that  
should recive the same design treatment.  IDs should be used to modify HTML elements that should receive unique design treatment.  IDs are  
useful because they will win out over all other CSS rules.

What are elements?
Elements are the building blocks of HTML.  An element consists of an openning tag, content, and a closing tag. 
What are tags?  
Tags indicate what type of building block an element is.  For example, a tag can indicate weather or not the element is a paragrpah, a heading  
a body, a title, etc.
What are attributes?  
extra bits of information about an HTML element, including id,class, title, or style that usually sit inside the opening  
tag and have "=" sign to indicate their value
What are forms? Forms are points of interaction with the user.  They allow users to input data.  
What is a div?  A division of a webpage that doesn't have any inherent semantic meaning, like paragraph or heading. They  
provide options for altering the composition and break up of the webpage

What are selectors?   
Primarily they are the names of html tags as well as attributes that give CSS the framework for applying  
design rules
What are properties?   
Properties are the different elements of style that can be applied to HTML.   For example, color, font-size, font-style, etc. 
What are values? 
Values indicate the specific attribute in HTML or property in CSS.  For example, in either branch of code, the value of the  
color would be the specific color.
How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
HTML is like a family tree, with granchildren inheriting the traits of their parents who also inherit the traits of thier parents.  
So, some CSS styles are inhereted from styles given to elements higher in the HTML hierarchy. 
What are two CSS attributes you can change to push an element around on the page? Margins and Borders 
What are the three different ways to include CSS in your project or use CSS to style a particular element?  
I don't understand this question.  Are you asking for three different CSS properties? You can use CSS to indicate different fonts  
you can use it to place different boxes on a page, or you can use it to provide different background colors and designs.

---
### Section 3: Git and Github  
What is Git?   
Git is a cloud-hosted version control system that facilitates historical revision tracking of projects for collaborative group
What is SCM?   
source code management system--includes all the processes needed to build, package, and deploy software. VCS is a subset.
What is a VCS?    
Version Control System -- any system or operating procedure that helps you keep track of a digital project, whether  
it be a website or an excel workbook, that is continually being motified.  Usually attempts to allow modifiers to back out of changes  
or compare previous versions to current versions.
Why is Git useful for a developer?    
As described previously, it's often necessary to undo changes or make comparisons between different versions of a digital  
project.  Developers may also want to see why certain changes were made. 
Why is Git useful for a team of developers?  
Git enables developers, who are all modifying different versions of the same project on different timelines, to merge thier  
changes and see and workthough any conflicting changes as well as access many other version control features.
How do you create a new Git repository for a project locally? git init project name   
How do you create it on Github?   
Select "+" in the upper righthand corner of any page on site, create name and optional description,choose whether it will  
be public or private, select "Initialize repository with READ.Me", select "Create Repository", write "git remote add origin  
plus git hub destination(provided) in local git terminal
How do you commit changes?    
git command -m"made changes, etc"
What is the difference between staging and committing changes?   
staging is adding files to be examined for changes and commiting changes is  
is making those changes a permanent, committed transaction for version control 
What is the difference between committing your changes and pushing them to Github?  
What is the command to check the status of your current repo in git?    
git status
What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
How can you look through your historical commits on the Github website?   
git log 
1. git log -p -#(of entries you want to see): shows difference introduced in each commit  
2. git lot --stat: shows abbreviated stats for each commit  
Github website:cick on the History tab
What is a "Merge"?  an action in github that folds new code into the core project
What is a "Pull Request"?    
an offer of your code changes to the central project maintainer, asking him/her to "pull" it
What is "Forking" a repo?   
"helping" or changing code in a copied project in your personal account so that you can offer them  
back to the core project later
What is "Cloning" a repo?   
A way to pull a project.  It brings all of the history and all of the branches of whatever repository you pull from github onto your local  disk, so you can work on, comment on etc, examine, etc
