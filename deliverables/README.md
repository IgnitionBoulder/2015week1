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
HTML is the structure of a website  

What is the role of CSS in a web page?  
CSS is the formatting and style of a website  

What is the role of Javascript in a web page?  
Javascript is a scripting language that displays outputs to make dynamic and interactive content on your website

---

### Section 2: HTML and CSS 101

#### meta
Why do we separate HTML and CSS?  
You seperate the HTML and CSS file so that you can make changes to the content on one file easily and then make changes to the style of the content efficiently with just one file instead of having to change each part of the html file.  

#### HTML
What are classes and IDs (and how are they different)?  
Id's and Classes are used to differentiate elements and classify them so that you can manipulate them and style them how you want. Classes can be used multiple times with different elements, but Id's can (should) only be used once with a certain element  

What are elements?  
An element is the markup that puts the html into content on your webpage starting with a start tag and ending with an end tag    

What are tags?  
Tags are the markup that differentiate each element using start tags and ending tags using < > 

What are attributes?    
Attributes add additional information to an element and are always in a name/value pair    

What are forms?  
forms are used to collect data from users. Users can enter data in a form using text boxes, check boxes or other input fields  

What is a div? 
A div seperates elements so that each section can be individually styled and formatted

What are selectors?  
In CSS, selectors are patterens used to select the different HTML elements that you want to style.  

What are properties?  
A CSS property is what appears before the colon and describes what part of the HTML element you want to style.  

What are values?  
The value comes after the property, and specifies what exact changes you want to make to that property in pixels, color values, etc.  

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
An html element gets its style by the css slector identifying the correct html element and attribute  

What are two CSS attributes you can change to push an element around on the page?  
Margin, padding  

What are the three different ways to include CSS in your project or use CSS to style a particular element? 
Making a seperate .css file and then putting a link element in the corresponding html file that directs the html document to that .css file, or putting the css stylesheet in the same document above the html document and link the two using a corresponding rel element  

---
### Section 3: Git and Github  
What is Git?  
Git is a VCS system that stores its data using a "snap shot" system, taking a sort of "screen shot" of your file and the changes that you made so that you can see your work and the changes you made over a period of time.

What is SCM?  
Software configuration management  

What is a VCS?  
Version Control Systems

Why is Git useful for a developer?
Because the file storing system insures file integrity and it's easy to colloborate with other people on a project and edit code    

Why is Git useful for a team of developers?  
Because the way the code is saved allows for everyone to see exactly what changes were made at a sertain period in time so that everyone can work together and understand when and why code was changed and add their own to it  

How do you create a new Git repository for a project locally?
Use the git init command 

How do you create it on Github?  
Click + and then click 'new repository'. Create a name and description for your new repository. Choose between Public or Private, initialize with a README, click Create Repository   

How do you commit changes?    
Click 'Commit Change' at the bottom of the page after you have made all of your changes to the repo 

What is the difference between staging and committing changes? 
When changes have been staged, that means that git knows about the change, but it is not permanent in the repository. The next commit will include the changes that were staged.

What is the difference between committing your changes and pushing them to Github?  

What is the command to check the status of your current repo in git?  
git status  


What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
The git log command shows your history of previous commits in reverese chronological order. One option is git log -p which shows the difference in each commit, or the command git log -2 which shows only the last two entries.  


How can you look through your historical commits on the Github website?  
Click on the "History" button at the top right of the repository.    

What is a "Merge"?   
When your changes have diverged from the current branch, you can merge them back together in the same branch by a git merge command.    


What is a "Pull Request"?  
After you fork a repo and make changes, you can make a Pull Request to have to original authors view your changes an decide if they want to indlude it in the final project.    

What is "Forking" a repo?  
Forking a repo means to create a new project based on another project that already exists  

What is "Cloning" a repo?  
Cloning a repo means to download a copy of the original code from a repository onto a local file on your computer  

Android file link http://htmlpreview.github.io/?https://github.com/Ledbettk/2015week1/blob/master/deliverables/android.html
