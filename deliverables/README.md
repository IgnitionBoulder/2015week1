# Week 1 Deliverable  

### Instructions  

In order to deliver homework consisting of questions and answers, just edit this file and commit the changes.  Once your answers are on Github, specifically in this file, you have delivered your homework.  
  
To answer questions, please just put the answer on the next line after the question.  Put a blank line after the answer to separate it visually from the next question.  

Example:  

**What is your name?**   
Jamie Finney

**What is your quest?**    
Maek the money don't let the money make me.  

**What is your favorite color?**  
Green!  

For projects on Code Academy, or other external exercises, please just paste a link into your deliverables file where we can see the result.  

### Section 1: The Front End
#### Required - Answer these questions in the deliverables file, and complete the following. 
**What is the role of HTML in a web page?**   
HTML is the skeleton of the page.

**What is the role of CSS in a web page?**    
CSS provides the styling for the page.

**What is the role of Javascript in a web page?**   
Javascript powers the interface of a page.

---

### Section 2: HTML and CSS 101

#### meta
**Why do we separate HTML and CSS?**    
HTML is static text/content on a page, while CSS styles and organizes the HTML and around it.  CSS is a much more arganized and faster way to style HTML rather than in the HTML file.

#### HTML
**What are classes and IDs (and how are they different)?**    
Classes and selectors help identify specific elements within HTML on CSS.  In the CSS, a class can be used to identify multiple HTML elements, or the whole class, while an id can identify a specific individual element.

**What are elements?**    
Elements are the actual content of the html file.  Elements=Bones in the skeleton.

**What are tags?**  
Tags identify elements.  This is the text that organizes and tells the element where to begin, end, and otther attributes.

**What are attributes?**    
Attributes are to elements as adjectives are to nouns.  They describe and identify specific characteristics of the element and belong within the opening tag.  

**What are forms?**  
Forms identify a basic interactive element in an html file.

**What is a div?**  
A div groups together sections of html between the <div> tags.  The div is then used in CSS to style this section of html. 

**What are selectors?**   
Selectors are what identifies the html element to be styled in CSS.

**What are properties?**  
Properties are how CSS specifies an attribute to be modified in html.

**What are values?**  
Vaues specify the property output (ie. font size). property:value;}

**How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?**  
Elements get their default style through "cascading."  An element's style can be defined by it's class, id, by what type of element it is (ie. p{) or by the defined value of its parent elements.  The most specific definition applies.

**What are two CSS attributes you can change to push an element around on the page?**   
Display and Position attributes move elements around a page.  Display will position the element ein relation to the elements around it, while Position will define how the element is displayed compared to the rest of the page, and then define particular positioning values.
Element{
  Display: inline;
  padding: 10px;
  }
Element{
  Position: relative;
  top: 5px;
  bottom: 5px;
  height: 100px;
  width:100px;
  }

**What are the three different ways to include CSS in your project or use CSS to style a particular element? **     
CSS can be put in the HTML file via in-line:
  Ex: <h1 style="color:red">Big Header Title</h1>
This only changes the element it is written in line with.
Internal:
  <style>
      selector{
        property:value;
      selector{
        property:value;
        }
  </style>
This will style all of the elements defined by the selectors in the HTML file.

External:
In a seperate CSS file.
selector{
  attribute:calue;
  }
This is ideal, as it keeps the html file clean and is more efficient.

**Android Logo**  
I did this

---
### Section 3: Git and Github  
**What is Git?**  
Git is a platform that allows developers to collaborate and track their progress. It is especially helpful for its ability to store files as snapshots over time and work locally.

**What is SCM?**  
Software Configuration Management

**What is a VCS?**  
A VCS allows developers to see each version of their file over time.  This allows them to explore different options and recover older versions without any consequences.

**Why is Git useful for a developer?**  
Collaboration, snapshot style saving, collaboration, ability to work locally.

**Why is Git useful for a team of developers?**  
Git allows developers to collaborate on a project together, but still experiment and work individually.  Different members can see each other's progress and have projects delegated betwen them.

**How do you create a new Git repository for a project locally?**  
git init - This creates a new repo in the current directory.  With <directory> it creates it in a new folder with just this new repo.

**How do you create it on Github?**  
+ in top right corner.

**How do you commit changes?**  
Click commit.

**What is the difference between staging and committing changes?**  
Staging allows you to edit your commits and format them before committing them.  You can then commmit changes to different edits individually without having to commit them before editing another area.

**What is the difference between committing your changes and pushing them to Github?**  
Committing changes will update the local repository, but not necessarily to the Github repo.  Comitting simply takes the snapshot to save the change, while pushing actually adds it to the Github repository.  The push is what actually contributes changes to the combined repo.

**What is the command to check the status of your current repo in git?**  
git status

**What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?**  
You can click history or add "commit" to the end of the file url in github.  In git, type git log to see the previous commits in reverse chronological order.  Entering "-p" shows the differences, while the addition of "-#" gives just that amount of the previous commits. "--stat" shows the number of file changes and how many lines were modified.  --pretty shows the previous commits in one line, with short, full, or fuller to change the amount of information displayed.

**How can you look through your historical commits on the Github website?**
History button.

**What is a "Merge"?**  
A merge is how you add your changes from one branch into the master branch, or the original branch you were working off of.

**What is a "Pull Request"?**  
This is how you get a repo from someone else.  

**What is "Forking" a repo?**  
Forking is how you clone a repo from the Github server to work on it as your own branch.  This is helpful if you are not a collaborator on that repo.

**What is "Cloning" a repo?**  
Cloning copies a repo to be edited locally.
