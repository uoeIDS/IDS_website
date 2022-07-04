---
title: "I can't work on my exercises in RStudio Cloud"
weight: 6
---

### I can't find my exercises on RStudio Cloud
Before working on them in RStudio Cloud, you have to __clone__ them from your repository on GitHub. To do this follow the instructions found on the <a id="OpeningaProject"> Opening a Project</a> page.


### A library I need is not loading in RStudio

If you have this problem it is most likely you are seeing this error in the console: 
`
Error in library(<package name>) : there is no package called '<package name>'
`

This means the package has not been installed yet. First please check that you are using the "IDS 2021/22" space on RStudio Cloud as all repositories created there should have the packages we need for the course pre-installed there.

However if you do need to still install a package for whatever reason, first you can try installing it from CRAN using:
```{r}
install.packages("<package name>")
```

This will not work for all packages as not all of them are on CRAN (e.g. "dsbox"). For these packages you will need to run something like the following:

```
install.packages("devtools")
devtools::install_github("<github_username/package_name>")
```

Generally, if you have problems installing something, go to a search engine and type in the name of the package to find its associated webpage. Most packages will have instructions on how to install them online.


### I can't clone a private repository from GitHub

First double check that you followed the <a id="GitHubSetup">GitHub Setup</a> and <a id="RStudioCloudSetup">RStudio Cloud Setup</a> instructions.

{{% notice note %}}
This issue is most likely to occour if you did the RStudio Cloud Setup before accepting the IDS organisation invitation.
{{% /notice %}}

You may have an issue when creating a "New Project from Git Repository" on RStudio Cloud, despite following the instructions, as shown below:

<img src="/images/troubleshoot/no-access-1.PNG"/>

To fix this issue...

1. On Rstudio Cloud, click on your profile icon in the top right, and then "Authentication" on the drop down box.

<img src="/images/troubleshoot/no-access-11.PNG"/>

2. If already ticked, untick the "Enabled" and "Private repo access also enabled" boxes 
<img src="/images/troubleshoot/no-access-2.PNG"/>

{{% notice note %}}
If these boxes are not already ticked, then your issue might be you have not followed the RStudio Cloud Setup instructions.
{{% /notice %}}

3. On GitHub, click on your profile icon, and "Settings" in the dropdown menu.

<img src="/images/troubleshoot/no-access-3.PNG"/>

4. On the left menu, select "Applications"

<img src="/images/troubleshoot/no-access-4.PNG"/>

5. Click on the "Authorized OAuth Apps" tab

<img src="/images/troubleshoot/no-access-5.PNG"/>

6. You should see "RStudio" listed as an authorized app. Click on the three dots (<span>&#8230;</span>), and then "Revoke".

<img src="/images/troubleshoot/no-access-6.PNG"/>

{{% notice note %}}
If you do not see "RStudio", then your issue might be you have not followed the RStudio Cloud Setup instructions.
{{% /notice %}}

7. Now go back to RStudio Cloud, go to the Authentication tab, and tick the "Enabled" and "Private repo access also enabled" boxes.

<img src="/images/troubleshoot/no-access-7.PNG"/>

- When you tick the "Enabled" box you should see the following page to authorize RStudio to access your GitHub account.

<img src="/images/troubleshoot/no-access-8.PNG"/>

- When you tick the "Private repo access also enabled" box you should see the following page to authorize RStudio to access __private repositories__ on your GitHub account.

<img src="/images/troubleshoot/no-access-9.PNG"/>

- Your Authentication page should now look something like below.

<img src="/images/troubleshoot/no-access-2.PNG"/>

You should not be able to create a "New Project from Git Repository" on RStudio Cloud.

<img src="/images/troubleshoot/no-access-10.PNG"/>