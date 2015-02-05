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
What is Git?  
What is SCM?  
What is a VCS?  
Why is Git useful for a developer?  
Why is Git useful for a team of developers?  
How do you create a new Git repository for a project locally?  
How do you create it on Github?  
How do you commit changes?  
What is the difference between staging and committing changes?  
What is the difference between committing your changes and pushing them to Github?  
What is the command to check the status of your current repo in git?  
What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
How can you look through your historical commits on the Github website?  
What is a "Merge"?  
What is a "Pull Request"?  
What is "Forking" a repo?  
What is "Cloning" a repo?  
