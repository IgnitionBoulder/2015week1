# Week 1 Deliverable  

### Instructions  

In order to deliver homework consisting of questions and answers, just edit this file and commit the changes.  Once your answers are on Github, specifically in this file, you have delivered your homework.  
  
To answer questions, please just put the answer on the next line after the question.  Put a blank line after the answer to separate it visually from the next question.  

Example:  

**What is your name?**
Alexandra Weiner

**What is your quest?**
I seek the Rails, yup that's it.  

**What is your favorite color?**
~~Green~~ edit:  No, blue.  Blue!  

For projects on Code Academy, or other external exercises, please just paste a link into your deliverables file where we can see the result.  

### Section 1: The Front End
#### Required - Answer these questions in the deliverables file, and complete the following. 
What is the role of HTML in a web page?  
It provides the framework and provides the meaning and content. 

What is the role of CSS in a web page?  
It creates the presentation of html.

What is the role of Javascript in a web page?  
It allows for interactivity.

---

### Section 2: HTML and CSS 101

#### meta
Why do we separate HTML and CSS?  
They are separated for organization (meaning) and clarity (presentation). 

#### HTML
What are classes and IDs (and how are they different)?  
In the CSS, a class selector is a name preceded by a full stop (“.”) and an ID selector is a name preceded by a hash character (“#”).
Classes are used for multiple items while IDs are used only once.

What are elements?  
Elements are tags and the content within them.

What are tags?  
The basic structure of an HTML document includes tags, which surround content and apply meaning to it.

What are attributes?  
Tags can also have attributes, which are extra bits of information. Attributes appear inside the opening tag and their values sit inside quotation marks. Their format is <tag attribute equals value

What are forms?  
They notate to take information and send it elsewhere. (i.e., collecting emails and sending it to a mailing list)

What is a div?  
Div is used to chunk code so information can be attached to it. 
The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

What are selectors?  
Selectors are the names given to styles in internal and external style sheets. Whereas HTML has tags, CSS has selectors. 

What are properties?  
For each selector there are “properties” inside curly brackets, which simply take the form of words such as color, font-weight or background-color.

What are values? 
A value is given to the property following a colon (NOT an “equals” sign) and semi-colons separate the properties.

How do CSS styles for a particular element get inherited? ie. how does an element get its "default" styles?  
You use the inherit value in the author or user style sheet. The inheritance comes from the designated attribute created by the author.

What are two CSS attributes you can change to push an element around on the page?  
Floats and in-line block can be used.

What are the three different ways to include CSS in your project or use CSS to style a particular element?  
text-decoration, text-align, text-indent can all be used to style CSS text. 

---
### Section 3: Git and Github  
What is Git?  
Git is a distributed version control systems. In these systems, clients don’t just check out the current version of the files and work from them – they mirror the entire version history. 

What is SCM?  
A source code manager is a software tool used by teams of programmers to manage source code. 
SCM is a broader term that encompasses all the processes needed to build, package, and deploy software -- this includes VCS.

What is a VCS?  
Version Control Systems is software that provides versioning functionality.

Why is Git useful for a developer?  
Git allows a single developer to make edits while tracking their changes.

Why is Git useful for a team of developers?  
Git allows for collaboration without confusion of using multiple files.

How do you create a new Git repository for a project locally?  
The following is a sample of how to create and push the code from your local database to a remote repo. 
<ul> 
<li>$ git init</li>
<li>Initialized empty Git repository in "url"/</li>
<li>$ cd /usr/local/remoteGit</li>
<li>$ git init --bare</li>
<li>Initialized empty Git repository in /usr/local/remoteGit</li>
<li>$ cd "url"</li>
<li>$ echo "hello" > hello.txt</li>
<li>$ git add hello.txt</li>
<li>$ git commit -m "Initial import" # commit to the local repository</li>
<li>$ git remote add origin /usr/local/remoteGit # configure the path to the remote repository</li>
<li>$ git push # push the code to the remote repository</li>
</ul>

How do you create it on Github?  
<p>
<ul>
<li> git init </li>
<li>git add .</li>
<li>git commit -m "first commit"</li>
<li>git remote add origin       copy the url from the github repo</li>
<li>git remote -v</li>
<li>git push origin master </li>
</ul>
</p>

How do you commit changes?  
Commit following the "first commit" and down from the above question

What is the difference between staging and committing changes?  
Committed means that the data is safely stored in your local database. Staged means that you have marked a modified file in its current version to go into your next commit snapshot. 

What is the difference between committing your changes and pushing them to Github?  
Committed is on your local database, while pushing them to GitHub stores them on GitHub. 

What is the command to check the status of your current repo in git?  
You run git status to check a current repo. 

What is the command to see the history of your previous commits (from the command line)?  What are a few interesting variations (sets of options)?  
<ul>
<li>git log</li>
<li>--follow</li>
<li>--source </li>
<li>--use mail-map</li>
</ul>

How can you look through your historical commits on the Github website?  
Use the history tab at the top of the page.

What is a "Merge"?  
A merge joins all changes to the master branch.

What is a "Pull Request"?  
Pull requests let you tell others about changes you've pushed to a repository on GitHub. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

What is "Forking" a repo?  
Forking a repository allows you to freely experiment with changes without affecting the original project.

What is "Cloning" a repo?  
This is just called duplicating. You need to run a special clone command against the original repository and mirror-push to the new one.
<p>
<ul>
<li>git clone --bare https://github.com/exampleuser/old-repository.git</li>
<li># Make a bare clone of the repository</li>

<li>cd old-repository.git</li>
<li>git push --mirror https://github.com/exampleuser/new-repository.git</li>
<li># Mirror-push to the new repository</li>

<li>cd ..</li>
<li>rm -rf old-repository.git</li>
<li># Remove our temporary local repository</li>
</ul>

<p>If you want to mirror a repository in another location, including getting updates from the original, you can clone a mirror and periodically push the changes.</p>
<ul>
<li>git clone --mirror https://github.com/exampleuser/repository-to-mirror.git</li>
<li># Make a bare mirrored clone of the repository</li>

<li>cd repository-to-mirror.git</li>
<li>git remote set-url --push origin https://github.com/exampleuser/mirrored</li>
<li># Set the push location to your mirror</li>
</ul>

<p>As with a bare clone, a mirrored clone includes all remote branches and tags, but all local references will be overwritten each time you fetch, so it will always be the same as the original repository. Setting the URL for pushes simplifies pushing to your mirror. To update your mirror, fetch updates and push, which could be automated by running a cron job.</p>
<ul>
<li>git fetch -p origin</li>
<li>git push --mirror</li>
</ul>
</p>
