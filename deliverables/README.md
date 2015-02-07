# Week 1 Deliverable  

### Instructions  

In order to deliver homework consisting of questions and answers, just edit this file and commit the changes.  Once your answers are on Github, specifically in this file, you have delivered your homework.  
  
To answer questions, please just put the answer on the next line after the question.  Put a blank line after the answer to separate it visually from the next question.  

---

**What is your name?**  
Alexander Maru

**What is your quest?**                      
I seek to gain a deeper understanding of web development, and specifically learn how HTML, CSS, 
JavaScript etc. work together to create dynamic web pages and applications.

**What is your favorite color?**                                    
I never have a good answer to this question, but if I were to pick one, I would say red. 
(It helps knowing that red is the very embodiment of strength and power!)

For projects on Code Academy, or other external exercises, please just paste a link into your deliverables file where we can see the result.  

### Section 1: The Front End
#### Required - Answer these questions in the deliverables file, and complete the following. 
**What is the role of HTML in a web page?**  
HTML provides the backbone structure to a web page. Most web pages can be thought of simply as
a list of structured text with headings, images, links etc. What HTML does is that it frames these structures
and produces a raw representation of our defined page. Later on, Cascading Style Sheets(CSS) can be applied 
for styling, and Javascript for interactivity.

**What is the role of CSS in a web page?**  
CSS is used to control a page's style or look. The overall appearance of a page we are used to seeing online is different from how a simple html file would appear. That is because CSS brings to the table the style aspect 
of web design, which, when used, makes our structured html file look dynamic and fluid.

**What is the role of Javascript in a web page?**  
Javascript is used to make a web page interactive.

---

### Section 2: HTML and CSS 101

#### Meta
**Why do we separate HTML and CSS?**  
Modularization, or in this case the separation of HTML and CSS, allow for efficiency, 
maintainability and reusability. This separation allows for low coupling, making updating or debugging 
our file much easier since only one part has to be dealt with, and it is easier to identify and modify.
On the same note, we can reuse our code much more easily when they are separated.


#### HTML
**What are classes and IDs (and how are they different)?**  
Classes are HTML attributes used to assign one or more subtypes to an element of a certain type.
IDs are attributes used to provide unique identifiers to elements within a document. The difference 
between them comes in that an ID has to be absolutely unique for an element within a page, whereas the
class attribute may be used to apply the same value to multiple elements in a page.

**What are elements?**  
Much like an atom that is made up of three sub-atomic particles consisting of protons, electrons and neutrons, 
similarly, an HTML element is made up of a starting tag, closing tag, and text in between. Elements are
the atomic building blocks of our HTML code.

**What are tags?**  
Tags are part of HTML elements that define the meaning and structure of our HTML code. They most often come
in pairs, namely start and closing tags. Some tags may define a table within our code, some a heading,
and we even define an html file using starting and closing html tags ("<html>,</html>", respectively).
Sometimes tags can be used for styling (eg. <"strong"> [text] </"strong">, makes our [text] bold etc.), but
for the most part, we leave the styling aspect to CSS.

**What are attributes?**   
HTML attributes are used to define different characteristics of elements. Attributes are entered within 
opening tags, and they affect the behaviour of whatever is in between the opening and closing tags
(eg. that can be a text, image etc). Most attributes have the following form: a type that initializes
a certain attribute (eg. "src" or "style"), followed by an equal sign, and then values in quotation marks.
If we want to set our font to Arial, for example, we would do it as follows (can be any random opening and
closing tag): <"p" "style="font-face:Arial""> [text] </"p"> (without the quotation marks, with the exception
of the ones after immediately after the equal sign.

**What are forms?**   
Forms are used to collect data from external source in the form of an input. This includes things like
names, emails, passwords etc, which the form then relays to a back-end application for processing.
The HTML tag for creating a form is <"form">[elements]</"form"> (without the quotation marks).

**What is a div?**  
A div is an element used to represent a block-level portion of HTML code, when no other HTML elements
are applicable. With the div tag, large sections can be defined and grouped. This allows for the defined
group to be worked on, eg. formatted with CSS or certain attributes to be applied etc. Its syntax is
<"div">[a section of html]</"div"> (without the quotation marks).


#### CSS
**What are selectors?**  
Selectors are used to basically "select" the part of html content we want to format. The different kinds
of selectors allow us to identify and style different parts of html. For example, a universal selector selects
an entire html file (ie. everything that is within the <"html"> ... </"html"> tags), and an element
selector selects specific elements with the same name. There are many more kinds of selectors, each with
their own set of parts they select.

**What are properties?**  
CSS properties are specific aspects of style we can modify within our html content. This includes, but is not
limited to, properties such as font, color, width or height, which take in values and apply the values to our
html content. 

**What are values?**  
Values are specific sets appended to their corresponding properties, which in unison format html content.
For example, a value of Arial for the font property sets the font of the selected html content to Arial.
The overall syntax of properties and values is "[property name]:[value];" (without the quotation marks).

**How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?**
In CSS, styles can be inherited from a parent element. So if, for example, a parent element is set to 
a color blue, then child elements without set color schemes will inherit that color and appear blue. Also, 
if style is re-defined, it over-rides the previous definition. Defining a style for a child element gives
the child element that style, over-riding whatever the parent element's style is.

**What are two CSS attributes you can change to push an element around on the page?**
Position is one attribute with which elements can be pushed around on a page. Top is another attribute that
can be used for positioning effect.

**What are the three different ways to include CSS in your project or use CSS to style a particular element?**
First method is creating a separate CSS file which can be linked to the web page being built. Second method
is creating a CSS block within the html code, most often being placed in between the opening and closing "head"
tags. And the third method is insertion of the CSS code right in the html tag itself.

#### Android
Put your html code in the `android.html` file in this folder.

---
### Section 3: Git and Github  
**What is Git?**                                                            
Git is a distributed revision control system. What this means is that a group of people can work on the
same project without having to share a common network.

**What is SCM?**                                                                  


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
