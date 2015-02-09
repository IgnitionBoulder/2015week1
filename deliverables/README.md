# Week 1 Deliverable  

**What is your name?**  
Christian Alic Kelley

**What is your quest?**                                                                                              
Become proficient at web development.    

**What is your favorite color?**                                                                                    
My favorite color is blue.  

Code Academy Profile: http://www.codecademy.com/albatross7817 

### Section 1: The Front End

What is the role of HTML in a web page?  
HTML provides the skeleton or structure upon which functional content within a web page will be built.  

What is the role of CSS in a web page?  
CSS provides the formatting and presentation of a web page that is separate from, but referenced to the HTML skeleton.  

What is the role of Javascript in a web page?  
The role of Javascript in a web page is multi-layered; for example: it allows for direct user interaction with the web page, it allows for one to build apps and games on a web page, it allows someone to access information on the internet.  These examples are introductory and are by no means exhaustive of the role Javascript has in a web page. 

---

### Section 2: HTML and CSS 101

#### Meta
Why do we separate HTML and CSS?  
We separate HTML and CSS for partly for conveneience and clarity, but mostly because they play different roles in designing a web page.  In addition to having slightly different syntaxes, HTML and CSS are designed to do different tasks; the HTML provides the skeleton of the web page, while the CSS provides the elements that make the base skeleton (i.e., HTML) more interesting, useful, and appealing.  Keeping them separate is both practical and asthetic.   

#### HTML
What are classes and IDs (and how are they different)?  
Classes and IDs are markers used to identify certain elements within the HTML code and then referenced to in the CSS code to apply functional content and structural attributes to them.  Classes can be appllied to many elements within the HTML file whereas IDs can be applied to only a single element.  Within the CSS file, the class formatting is referenced with '.class' and the ID formatting is referenced with '#ID' (where the 'class' and 'ID' are the specific ones created in the HTML file.  

What are elements?  
HTML elements are entities that comprise different parts of a webpage, such as a title, headings, paragraphs, lists, and so on.  These HTML elements can be combined to construct useful and practical web pages.  

What are tags?  
HTML tags are markers that are used to construct the elements.  An HTML tag is typically comprised of an opening <-> and closing </-> where '-' is the type of element to be constructed; for example, 'p' for paragraph, 'ol' for ordered list, 'li' for a list element, and so on.  

What are attributes?  
Attributes are indicators used within tags to modify HTML elements.  They consist of a reference word, followed by an equals sign, and then a directive placed in quotation marks.  Attributes are placed after the initial opening tag bracket and tag type but before the initial closing bracket; it is possible to use several attributes within the same tag  

What are forms?                                                                                                       
HTML forms are elements designed to allow users to directly input information, select an option from a list, or designate certain values that apply to that user.  These HTML forms allow users to send information to a website's server directly to be processed.  

What is a div?                                                                                                        
An HTML div is an element that when used properly with opening and closing tags can be used to make different sections (or divisions) within a web page.  

#### CSS
What are selectors?  
CSS selectors identify the HTML elements that they will be modifying.  THey precede a set of curly brackets.  

What are properties?  
CSS properties determine what to do to the HTML elements within the curly brackets assigned to each selector.   

What are values?  
Values are the specific instructions associated to each property determining what modifications ultimately will be applied to the HTML elements associated with each selector.  

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
CSS styles for a a particular element get inherited from their parent values.  If no styles have been specified, then the default values are applied automatically.  The default values are assigned within each individual web browser.  

What are two CSS attributes you can change to push an element around on the page?  
Two CSS attributes a programmer can change to push an element around on the page are 'float' and 'position'.  

What are the three different ways to include CSS in your project or use CSS to style a particular element?  
We can use the global CSS selector which will be applied to all elements.  We can define a class and assign it to many different elements within the HTML code and then modify the class in CSS.  And we can define an ID for a single HTML element and then modify its properties in CSS.  

#### Android
Put your html code in the `android.html` file in this folder.

---
### Section 3: Git and Github  
What is Git?  
Git is a distributed revision control system used for software development.  

What is SCM?  
Source Code Management (SCM) is software that allows developers to design and implement changes to codes in a manner that can keep each developer's files separate but can also integrate code from many developers files to apply changes and prevent these changes from being altered without permission.  

What is a VCS?  
A Version Control System (VCS) is a stand-alone application that can be embedded in software packages and used to track edits made by individual programmers, allow for changes and modifications to be made or undone, and also can be used to compare and merge separate files.  

Why is Git useful for a developer?  
Git is useful for a developer because it provides a network and server indepenent system that provides a developer a centralized location to create, modify, and track changes to their code.  And its free!  

Why is Git useful for a team of developers?  
Git is useful for a team of developers because they can compare files, track changes to one another's files, and merge files or parts of files to create new more useful code.  Ultimately, Git allows a team of developers to be more efficient at crating and maintaining useful code in an enviroment that allows collaboration and teamwork rather than each developer using their own separate programs.  And it's free!  

How do you create a new Git repository for a project locally?  
The command line is used to creat a new Git repository for a local project.  A basic command line instruction to create a Git repository may look something like this: '$ git init'.  

How do you create it on Github?  
From the top of a user's webpage on Github is a '+' that brings down a menu, the first option of which is used to create a new repository directly.  

How do you commit changes?  
Changes can be committed directly within Github by clicking on 'Commit changes' when one is ready.  They can also be committed through the command line with '-commit'.  When using the command line, committed changes then need to be 'pushed' to Github to update to file directory from the local system to the Github directory.  When the changes are committed on Github directly, they are pushed onto the directory automatically.  

What is the difference between staging and committing changes?  
On Github, staging changes is just editing a file; the changes do not take effect until they have been committed.  In this sense, committing changes saves these changes to your file; that is, staged changes are unsaved while committed changes are saved.  

What is the difference between committing your changes and pushing them to Github?  
From the command line, commiting your changes saves the staged changes you've made to your local file on your own local system.  While these changes will appear when viewing this file on your system, the changes will not appear on Github until they have been pushed onto the appropriate directory.  

What is the command to check the status of your current repo in git?  
From the command line, simply type 'git status' and the current state of the repository  will be returned.  

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
To see the history of previous commits from the command line use the 'git log' command.  There are many options to go with the 'git log' command.  Adding '-p' shows the difference introduced in each commit made.  Using '--stat' shows statistics for files modified via each commit while '--shortstat' displays only the changed/insertions/deletions line that is called from the --stat command.  The '--pretty' option allows one to change the output format from defualt to other alternatives, such as '=oneline' (prints each commit on a single line); and the options '=short', '=full', and '=fuller' allow one to specify less or more information regarding each commit as desired.  

How can you look through your historical commits on the Github website?  

What is a "Merge"?  
What is a "Pull Request"?  
What is "Forking" a repo?  
What is "Cloning" a repo?  
