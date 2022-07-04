---
title: "Opening a Project"
weight: 3
---
These instructions are used to set up a new project in RStudio Cloud from a GitHub repository ("repo").

{{% notice warning %}}
You cannot carry out the steps on this page unless you have created your GitHub account, accepted the invitation to join the GitHub organization, signed up for RStudio Cloud using our course workspace, and linked your RStudio Cloud and GitHub accounts. Please ensure you have completed the <a id="GitHubSetup">GitHub Setup</a> and <a id="RStudioCloudSetup">RStudio Cloud Setup</a> first.
{{% /notice %}}


If you just need to copy ("clone") the repo to your workspace (e.g. for <strong>Application Exercises</strong>) you will only need to carry out the first part of these instructions (1-4). For <strong>Homework</strong>, <strong>Workshop</strong>, and the <strong>Project</strong> tasks, where you need to "pull" and "push" changes to and from GitHub, you will need to complete the full set every time you set up a new project (unless you use a password manager).

### Cloning
The first step is always to bring files into RStudio Cloud so that you can edit them, run them, view your results, and interpret them. This action is called **cloning**.

The next few steps will walk you through the process of getting information of the repo to be cloned, cloning your repo in a new RStudio Cloud project, and getting started with the analysis.

<ol>

<li>
  On the GitHub page of the repo you wish to clone, click on the green <strong>Code</strong> button, select <strong>HTTPS</strong> (this might already be selected by default, and if it is, you'll see the text <em>Use Git or checkout with SVN using the web URL</em>).
  Click on the clipboard icon (<i class="fas fa-clipboard"></i>) to copy the repo URL.
  
  <img src="/images/troubleshoot/clone-repo-link.png">
  
  {{% notice note %}}
  Assignment repos all have the same format:
  `<code>-<num>-<assignment name>-<username/team name>`. So for example, your repo for the first homework (not assessed) would look like "hw-00-pet-names-MyUsername", and the first lab looking like "lab-00-hello-ids-MyTeam". If there is no GitHub repo created for you for an assignment, it is likely the teaching staff do not have your GitHub username when the assignment was issued. Please follow the first time setup instructions on the <a id="troubleshoot">Setup & Troubleshooting</a> page.
  {{% /notice %}}
</li>

<li>Go to <a id="RStudioCloud">RStudio Cloud</a> and then <strong>navigate to the course workspace</strong> via the left sidebar (<i class="fas fa-bars"></i>). It's very important that you do this for two reasons:
  <ul>
    <li>It's only when you're in the course workspace that you'll be able to benefit from R packages pre-installed for you so that your project can be configured correctly.</li>
    <li>It's only when you're in the course workspace that your usage of RStudio Cloud won't count towards their free usage limits. RStudio offers free usage of their Cloud service, but they cap it at 15 hours. The university has already paid for an RStudio Cloud account for you, and you want to make sure you're taking advantage of that, and not using up your personal free hours.</li>
  </ul>

<img src="/images/troubleshoot/course-workspace.png">

Before you proceed, confirm that you are in the course workspace by checking out what's on your top bar in RStudio Cloud.
</li>

<li>Click on <strong>New Project</strong> at the top right, then click on <strong>New Project from Git Repository</strong>.
<img src="/images/troubleshoot/10-new-project.png"/>
</li>

<li>
In the pop-up window, <strong>paste the URL</strong> you copied from GitHub using Ctrl+V (Windows)/Cmd+V (Mac). Make sure the box for <strong>Add packages from the base project</strong> is checked (it should be, by default) and then click <strong>OK</strong>.

<img src="/images/troubleshoot/11-url.png"/>
</li>

</ol>

{{% notice info %}}
If you have no need to "pull" or "push" the project to and from GitHub, you are now done <i class="fas fa-glass-cheers"></i>. If not then you've got a few more steps to go <i class="far fa-tired"></i>.
{{% /notice %}}

### Push and Pull Changes
When working on assignments in RStudio Cloud, you will be instructed to make **commits** (snapshots of your changes), as well as **push** and **pull** your work to and from to GitHub.

The next few steps will walk you through the process of setting up your RStudio Cloud project with your GitHub credentials.

<ol start="5">
<li>In your RStudio Cloud Project, click on the <strong>Git</strong> tab in the top-right panel, and click on <strong>Pull</strong>.</li>
<img src="/images/troubleshoot/12-rstudio-pull.png"/>
<li>You will be prompted for your username.  Enter your <strong>GitHub</strong> username, and click <strong>OK</strong>.</li>
<img src="/images/troubleshoot/13-username.png"/>

<li>A new box will appear asking for a password. <strong>Do not</strong> enter your GitHub password in here, it won't work and you will get an error message that looks like this... 
<img src="/images/troubleshoot/pass-error.PNG"/>

Instead, as mentioned in the error above, GitHub now requires a "personal access token" instead of your GitHub password. To get one, leave this tab open, and open a new tab in your browser. Go to <a id="GitHub">GitHub</a> in this tab, and log in.</li>

<li>In GitHub, click on your profile image at the top left, then click on <strong>Settings</strong>.</li>
<img src="/images/troubleshoot/01-github-menu.png"/>

<li>From the side menu, choose <strong>Developer Settings</strong>.</li>
<img src="/images/troubleshoot/02-github-develop.png"/>

<li>Choose <strong>Personal access tokens</strong>.</li>
<img src="/images/troubleshoot/03-github-PAT.png"/>
{{% notice note %}}
If you already have existing tokens, you should now see a list of all your tokens here. To create a new token click <strong>Generate new token</strong>.
{{% /notice %}}

<li>You are now creating a "New personal access token". Enter a descriptive name of the project you're creating the token for in the "note" box (e.g. "Homework 00").</li>

<li>Choose <strong>30 days</strong> for the <strong>Expiration</strong>.</li>
{{% notice note %}}
You'll have to create a new token if your token expires (i.e. thirty days after you made it) and you're still working on that project.  
{{% /notice %}}

<li>Under "Select scopes", tick the box next to <strong>repo</strong>, which will also tick all the sub-options.  Leave all the other boxes un-ticked.</li>
<img src="/images/troubleshoot/05a-github-tickboxes.png"/>
<img src="/images/troubleshoot/05b-github-tickboxes.png"/>

<li>Click on <strong>Generate token</strong>.</li>
<img src="/images/troubleshoot/06-github-gen-token.png"/>

<li>You will now be presented with the token, which is a long string of characters.  Click on the clipboard icon (<i class="far fa-clipboard"></i>) to copy the token, so you can paste it into RStudio Cloud.</li>
<img src="/images/troubleshoot/07-github-copy.png"/>
{{% notice note %}}
If you navigate away from this page without copying the token, you won't be able to see it again.  That's no problem, you'll just need to go back to step 8 and create a new token. After step 10, you should see a list of all your tokens, at which point you should choose the option to <strong>Delete</strong> the token that you didn't manage to copy before moving to step 11.  
{{% /notice %}}

If you prefer, you can store this token in a password manager, in which case you can use it for multiple projects until it expires.  

{{% notice warning %}}
You <strong>should never</strong> store it in a plaintext, unencrypted file, just as you should never store passwords in this way!
{{% /notice %}}

<li>Go back to the tab with RStudio Cloud, and paste the token into the box, using Ctrl+V (Windows)/Cmd+V (Mac).  Click <strong>OK</strong>.</li>
<img src="/images/troubleshoot/14-token-entry.png"/>
<li>Click <strong>Close</strong>.</li>
</ol>

{{% notice info %}}
You are now properly done <i class="fas fa-glass-cheers"></i>! To test that it works, click the <strong>Pull</strong> button again: you shouldn't see any prompts for your username or password.
{{% /notice %}}
