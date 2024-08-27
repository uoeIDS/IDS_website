---
chapter: true
pre: "<b>2. </b>"
title: "2. Wrangling and Tidying Data"
menuTitle: "Wrangling and Tidying Data"
weight: 2
tags: ["week 2", "tasks", "videos", "assignments", "readings", "tutorials"]
description: "Week 2 (23 Sep 2023 - 27 Sep 2023): Data wrangling, joining, and tidying."

hidden: no
---

# Wrangling and Tidying Data

_Week 2 (25 Sep 2023 - 29 Sep 2023)_

Getting started with data science by wrangling data, Yee-Haw!

## Lectures


<!--
| <div style="width:50px;text-align:center">No.</div> | <div style="width:250px;text-align:left">Title</div> |  <div style="width:80px;text-align:center">Slides</div> | <div style="width:170px;text-align:center">Additional Links</div> | -->
| <div style="text-align:center">No.</div> | <div style="text-align:left">Title</div> |  <div style="text-align:center">Slides</div> | <div style="text-align:center">Additional</div> |
|:---:|:---------------------|:--------:|:------|
| 03  | Tidy Data and Data Wrangling | <span><a id = "lecture03"><i class="fas fa-desktop fa-lg"/></a></span> | <span><a id = "GHL03">Raw<i class="fab fa-fw fa-github"/></a></span> |
| 04  | Data Types and Classes |<span><a id = "lecture04"><i class="fas fa-desktop fa-lg"/></a></span> | <span><a id = "GHL04">Raw<i class="fab fa-fw fa-github"/></a></span> |


<br>
<p  style="text-align: left"> 
<font size=4pt><b>Lecture Recordings</b></font>
<span class="fa-stack" style="scale:70%">
    <i class="fas fa-backward fa-stack-1x fa-1x fa-flip-horizontal" style="color:#f37361; box-sizing: content-box; line-height: 24px; width: 24px; height: 24px; border-radius: 100%; border-style: solid; border-width: 4px;"></i>
</span>
<br>
Lecture recordings are only available for IDS students via the University of Edinburgh virtual learning environment. To access the recordings, go to the Introduction to Data Science area on LEARN ULTRA and select <em>Lecture Recordings</em>  under the <em>Course Content</em> section. This will open <em>echovideo</em> where you will find a list of all lecture recordings to watch once they become available. 

</p>

## Tasks

{{% notice warning %}}
If you have not completed the <em>first time setup instructions</em> found on the <a id="troubleshoot">Setup & Troubleshooting</a> page, please follow these now.
{{% /notice %}}


<ol>
  <li>Watch the <a href="#videos and readings">Videos and readings</a>.</li>
  <li>Complete the <a href="#assignments">Assignments</a>.</li>
</ol>

## Videos and readings

<p style="text-align: left">Some of this material is required and some of it is optional. We expect you to watch the required videos and read the required reading. This required material is part of the course so it may be assessed in the assignments and it may not be covered in the lectures. The optional material is extra reading for those that are interested!</p>

<!--
| <div style="width:50px"></div>  | <div style="width:420px"></div>  |  <div style="width:200px"></div> |

|:---:|:---|:---:|-->

|    |    |    |
|:--:|:---|:--:|
| <i class="fas fa-book"></i> | R4DS: <a id="R4DS4">Chp 4 - Workflow: basics</a> | Optional |
| <i class="fas fa-book"></i> | R4DS: <a id="R4DS5">Chp 5 - Data transformation</a> | **Required** |
| <i class="fas fa-book"></i> | R4DS: <a id="R4DS15">Chp 15 - Factors</a> | **Required** |
| <i class="fas fa-book"></i> | R4DS: <a id="R4DS16">Chp 16 - Dates and times</a> | **Required** |
| <span style="color: red;"><i class="fab fa-youtube fa-lg" /></span> | <a id = "YT_Computerphile_time">Computerphile: The problem with time and timezones</a> | Optional |
| <i class="fab fa-readme"></i> | <a id="NatRepro">1,500 scientists lift the lid on reproducibility</a> | Optional |

<!--
| <i class="fab fa-readme"></i> | <a id="tidydata">Tidy Data</a> | Optional |
| <i class="fas fa-file-video"></i> | <a id="MHL05extra">L05 supplement</a>: extra explanation of logical operations in R | Optional |
-->





## Workshop

<p style="text-align: left"> The lab sheet can be accessed the day before the workshop, and the solutions the day after the workshop.</p>

<!--
| <div style="width:300px;text-align:left">Laboratory Title</div> | <div style="width:170px;text-align:left">Links</div> | <div style="width:180px;text-align:left">Date</div> |
|:---|:---|:---|
| Lab02: Make a sad plot better | <li><a id="LAB2I">Instructions</a></li> <li><a id="LAB2R">Repository</a></li><li><a id="LAB2K">Solutions</a>(<a id="LAB2Kraw">Raw</a>)</li> | Fri, 29 Sept, 16:00 UK  |
-->

| <div style="text-align:left">Laboratory Title</div> | <div style="text-align:left">Links</div> | <div style="text-align:left">Date</div> |
|:---|:---|:---|
| Lab01: UK Attractions | <li><a id="LAB1I">Instructions</a></li> <li><a id="LAB1R">Repository</a></li><li><a id="LAB1K">Solutions</a>(<a id="LAB1Kraw">Raw</a>)</li> | Fri, 29 Sept |

<!--
## Assignments

<p style="text-align: left">If you are having difficulty accessing your HW or Lab repo, see troubleshooting advice <a id="troubleshoot">here</a>.</p>

| <div style="width:300px;text-align:left">Assignment Title</div> | <div style="width:170px;text-align:left">Links</div> | <div style="width:180px;text-align:left">Due</div> |
|:---|:---|:---|
| OQ02: Data Wrangling | <li><a id="OQ2">Quiz</a></li> | Mon, 10 Oct, 12:00 UK |


<p style="text-align: left">
<b>Reminder</b>: Homework assignment <em>hw-01</em> is due Fri, 7 Oct, 12:00 UK time.
</p>


## Interactive R tutorials

<p style="text-align: left"> The following are interactive R tutorials, designed to give you more practice with R. These are optional, but the "Road Traffic Accidents"" dataset shows up in your next homework assignment as well, so you might want to go through that one so that you can gain familiarity with it. If you’re struggling with any of the topics covered this week, we strongly recommend you work through the second tutorial as well.</p>

|  <div style="width:480px"></div>  |  <div style="width:200px"></div>  |
|:---|:---|
| <a id="RT4">Work with data</a> | Extra practice |
| <a id="AE3">Application exercise 3 - Hotels</a> | Help: <a id="OpeningaProject">Opening a Project</a> |
-->

