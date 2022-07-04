---
title: "RStudio Cloud Setup"
weight: 2
---

<ol>
<li>Go to <strong>Learn</strong> and click on the <strong>Join RStudio Cloud</strong> link to sign up for a free RStudio Cloud account which will be automatically enrolled in our course’s space.</li>
  <ul>
  <li>Feel free to try launching a project and exploring.</li>
  </ul>
  
<img src="/images/troubleshoot/rstudio-cloud.png"/>
{{% notice warning %}}
You cannot do the remaining steps unless you have created your GitHub account and accepted the invitation to join the GitHub organization. Please ensure you have completed the <a id="GitHubSetup">GitHub Setup</a> first.
{{% /notice %}}
The rest of these instructions are used to connect your RStudio and GitHub accounts.
<br><br>
<li>In <a id="RStudioCloud">RStudio Cloud</a>, click on your name on the top right corner to open the right menu.</li>
<li>Then, click on <strong>Authentication</strong>.</li>
<img src="/images/troubleshoot/github-auth-1.png"/>
<li>In the Authentication window, check the box for <strong>Enabled</strong>.</li>
<img src="/images/troubleshoot/github-auth-2.png"/>
<li>In the next window, click on the green box that says “Authorize RStudio”.</li>
<img src="/images/troubleshoot/github-auth-3.png"/>
<li>Back in the Authentication window, check the box for <strong>Private repo access</strong> also enabled, and once again, on the green box that says “Authorize rstudio” in the next window.</li>
<img src="/images/troubleshoot/github-auth-4.png"/>
{{% notice note %}}
At this point you should also make sure that the course organization shows up for you under Organization access. If it does not, this means you have not yet accepted the GitHub invitation to join the course, and you should go back and do that.
{{% /notice %}}
<li>Once you’re done, both of these boxes should be checked.</li>
<img src="/images/troubleshoot/github-auth-5.png"/>
<li>To confirm that you’ve successfully linked up your GitHub and RStudio Cloud accounts, go to <a href="https://github.com/settings/applications">GitHub settings > Applications</a>. You should see RStudio listed as an authorized app under Authorized OAuth Apps. If you don’t this is a good time to ask for <a id="help">help</a>.</li>
<img src="/images/troubleshoot/github-auth-6.png"/>
</ol>
