---
title: "GitHub Setup"
weight: 1
---

## GitHub Account

__If you do not currently have a GitHub account__, please [sign up](https://github.com/signup).</li>
<li>See <a id="gituseradv">here</a> for advice on selecting a username.</li>
<li>After this, make sure to verify your GitHub email address.</li>

## Install Git

<strong>Git</strong> is a version control system. It helps you to write code in teams, as you must do for this course, without breaking each other's code. It also lets you keep a record of the changes you make, so that you can go back
to earlier versions, if you need to. 
<ul>
<li> To install git follow the instructions <a href="https://www.git-scm.com/">here</a>. On Windows you should use the default options. 

<li> Linux systems often have Git installed already. If not, typing something like

<pre>
<code>
sudo apt install git
</code>
</pre>

should install it. 


<li> For Mac or Linux systems you also need to install the Git Credential Manager Core (this is automatically installed for
Windows). Instructions are <a href="https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git">here</a>. Linux can be slightly fiddly - try using the plain text option 4 for credential storage.

<li> For more help, try the instructions <a href="https://happygitwithr.com/install-git.html">here</a>.

</ul>

## Link Git and GitHub

Git is a version control system that keeps track of changes to projects. GitHub is an internet repository where these projects are stored. We will work with projects that are stored on your own computer but will regularly sync local data to the online GitHub repository. To do this, we need to make sure that your local Git installation can communicate with your online GitHub account.  

<ul>
<li> You will need to use a <strong>terminal</strong> to talk to Git. In RStudio you can launch a terminal using <em>Tools>Terminal</em> (the terminal will be in the bottom left panel). Make sure you have re-started RStudio after installing Git before you do this. There are other terminal options but these depend on your operating system. See <a href="https://happygitwithr.com/shell.html">here</a> for some suggestions. 
<li> Once you have opened a terminal window, try typing 

<pre>
<code>git --version</code>
</pre>

This should return the version number of Git that you have installed. For me this is:

<pre>
<code>git version 2.37.0.windows.1</code>
</pre>

<li> You then need to link your Git installation to your GitHub account. To do this, type

<pre>
<code>
  git config --global user.name 'Jane Doe'
  git config --global user.email 'jane@example.com'
  git config --global --list
</code>
</pre>

in the terminal, replacing <em>Jane Doe</em> by your name and <em>jane@example.com</em> by the email address <strong>that is associated with your GitHub account</strong>.

</ul>

## Link GitHub and RStudio


RStudio has inbuilt tools that make it easier to work with Git and GitHub. The final step is to check that we can link RStudio to GitHub.

### Set up a new GitHub repository

First we need to set up a new <strong>repository</strong> (repo) to work on:
<ul>
<li> Login to your GitHub account <a href="https://www.github.com/">here</a>, click on <em>Repositories</em> and then click on <em>New</em> to set up a new repository.
<li> Follow the instructions. If you are working on assessed coursework you will need to set your repository to private. Add a README file so that you have something to edit.
<li> You can add files directly to your repo via the web interface, but below we will see how to add files using RStudio. 
</ul>
<br><br>


### Use RStudio to clone the repository to your local computer

The first step is always to bring files into RStudio so that you can edit them, run them, view your results, and interpret them. This action is called **cloning**.

The next few steps will walk you through the process of getting information from the repo to be cloned, cloning your repo in a new RStudio project, and getting started with the analysis.


<ol>
<li> In the new repository you have created on GitHub, click on the green <strong>Code</strong> button, select <strong>HTTPS</strong> (this might already be selected by default, and if it is, you'll see the text <em>Use Git or checkout with SVN using the web URL</em>).
  Click on the clipboard icon (<i class="fas fa-clipboard"></i>) to copy the repo URL.
  
  <img src="/images/troubleshoot/clone-repo-link.png">
  
<li> In RStudio open a new project using <br>
<em>File > New Project > Version Control > Git</em>. <br>

In <em>Repository URL</em>, paste the URL of your new GitHub repository.

<li> Accept the default name, check the project is being saved in the place you want and click <em>Create Project</em>.

<li> These steps should open your test GitHub project. If you check in the files pane (bottom right panel in RStudio) you should see the README file you created. Try opening this, editing it and saving the changes. 
</ol>

Well done - you have successfully cloned the repo!

### Pushing changes back to GitHub.

In the last section we saw how to clone a repo, but we also need to be able to sync changes we make in RStudio to GitHub. This is known as **pushing** changes to the repo. The following steps explain how to do this:

<ol>
<li> Click the Git tab in the upper right pane in RStudio. Check the staged box for the README file and click commit. A Git box should pop up. 
<li> Write a commit message describing the change you have made and click commit again. Now click push (the green arrow). This pushes your changes to GitHub.
<li> Now go back to the online GitHub repository and hit refresh. Find your README file - it should show the changes you just made in RStudio.
</ol>
<br><br>

## Set up a GitHub repository for coursework

For the homework and labs you will be provided with a template file to start off with. This file will be uploaded to a repository on the course GitHub page. In this section we go through how to copy this repository containing the template file to your own account. For the homework you will need to use a **private** repository. This is so that others will not be able to see your work. 


<ul>
<li> Login to your GitHub account <a href="https://www.github.com/">here</a>, click on <em>Repositories</em> and then click on <em>New</em> to set up a new repository.
<li> Click <em> Import a repository </em>.
<li> Open the <a id="ids2022Git">course GitHub page</a> in a different tab, navigate to the folder you want to copy and get the URL by clicking on the green code button and copying the URL shown. 
<li> Go back to your own GitHub account and paste the URL into the <em>"Your old repository’s clone URL"</em> box.
<li> Add a repository name. Don't use any spaces in this.
<li> Choose whether the repository should be private (for homework) or public (for labs).
<li> Select <em> Begin import</em>
</ul>


For group work, one person can set up the repo and invite the rest of their team to collaborate on it. To do this:
<ul>
<li> Log on to GitHub, nagivate to your repo, and click on Settings.
<li> Click on Manage Access from the left hand menu, and then on Invite a collaborator - you will need their github user name.
<li> Note that collaborators have to accept the invitation before they can save work (push) to the github repo – this applies whether the repo is private or public.
</ul>

Once your new repository is set up you will need to clone it to RStudio as described <a href="#use-rstudio-to-clone-the-repository-to-your-local-computer">above</a>. 


## Help

Congratulations! You have now set up RStudio to work with GitHub. 
<br><br>

If you need more help with any of this a good place to start is the information <a href="https://happygitwithr.com">here</a>. The lecturers and tutors will also be available to work through these steps with you in the workshops on Fridays. 

There are IT support drop in sessions in weeks 1 and 2 on Tuesdays from 11-1 in mathsbase. There will be tutors available to help you with these steps. 

