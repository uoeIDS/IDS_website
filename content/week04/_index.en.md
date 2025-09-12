---
chapter: true
pre: "<b>4. </b>"
title: "4. Uncertainty quantification"
menuTitle: "Uncertainty quantification"
weight: 4
tags: ["week 4", "tasks", "videos", "assignments", "readings", "tutorials"]
description: "Week 4: Uncertainty quantification and hypothesis testing with bootstrap."

hidden: no
---
  <!-- set 'hidden: true' to hide content, or 'hidden: no' to show-->
  
  
  # Uncertainty quantification
  
  _Week 4_

Uncertainty quantification and hypothesis testing with bootstrap.

## Lectures

<!--
| <div style="width:50px;text-align:center">No.</div> | <div style="width:250px;text-align:left">Title</div> |  <div style="width:80px;text-align:center">Slides</div> | <div style="width:170px;text-align:center">Additional Links</div> | -->
| <div style="text-align:center">No.</div> | <div style="text-align:left">Title</div> |  <div style="text-align:center">Slides</div> | <div style="text-align:center">Additional</div> |
|:---:|:---------------------|:--------:|:------|
  | 07  | Uncertainty Quantification | <span><a id = "lecture07"><i class="fas fa-desktop fa-lg"/></a></span> | <span><a id = "GHL07">Raw<i class="fab fa-fw fa-github"/></a></span> |
  | 08  | Hypothesis testing | <span><a id = "lecture08"><i class="fas fa-desktop fa-lg"/></a></span> | <span><a id = "GHL08">Raw<i class="fab fa-fw fa-github"/></a></span> |

{{% notice warning %}}
The in-class test will take place this week, during the Wednesday lecture.
{{% /notice %}}
  
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
<!--
{{% notice warning %}}
If you have not completed the <em>first time setup instructions</em> found on the <a id="troubleshoot">Setup & Troubleshooting</a> page, please follow these now.
{{% /notice %}} -->

<ol>
  <li>Watch the <a href="#videos and readings">Videos and readings</a>.</li>
  <li>Attend the <a href="#workshop">workshop</a>.</li>
  <li>Complete the <a href="#assignment">Assignments</a>.</li>
</ol>

## Videos and readings


<p style="text-align: left">Some of this material is required and some of it is optional. We expect you to watch the required videos and read the required reading. This required material is part of the course so it may be assessed in the assignments and it may not be covered in the lectures. The optional material is extra reading for those that are interested!</p>

<!---
<p style="text-align: left">You have two options for watching the course videos, on YouTube or on MediaHopper. You can also find a playlists for all course videos on YouTube <a id="playlistyt">here</a> and on MediaHopper <a id="playlistmh">here</a>.

| <div style="width:50px;text-align:center">No.</div> | <div style="width:250px;text-align:left">Title</div> | <div style="width:80px;text-align:center">YouTube</div> | <div style="width:100px;text-align:center">MediaHopper</div> |  <div style="width:80px;text-align:center">Slides</div> | <div style="width:170px;text-align:center">Additional Links</div> |
|:---:|:---------------------|:-------:|:-----------:|:--------:|:------|
| 01  | Keeping up with IDS: Week 2 | <a id="W2L1YT"><span style="color: red;"><i class="fab fa-youtube fa-lg" /></span></a> | <a id="W2L1MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"/></span></a> | - | - |
| 02  | 	Data and visualisation      | <a id="W2L2YT"><span style="color: red;"><i class="fab fa-youtube fa-lg" /></span></a> | <a id="W2L2MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"/></span></a> | <a id="W2L2S"><span style="color: #4b5357;"><i class="fas fa-desktop fa-lg"/></span></a>  | <li><a href="/errata#W202">Errata</a></li> |
| 03  | Visualising data with ggplot2    | <a id="W2L3YT"><span style="color: red;"><i class="fab fa-youtube fa-lg" /></span></a> | <a id="W2L3MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"/></span></a> | <a id="W2L3S"><span style="color: #4b5357;"><i class="fas fa-desktop fa-lg"/></span></a> | - |
| 04  | Visualising numerical data   | <a id="W2L4YT"><span style="color: red;"><i class="fab fa-youtube fa-lg" /></span></a> | <a id="W2L4MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"/></span></a> | <a id="W2L4S"><span style="color: #4b5357;"><i class="fas fa-desktop fa-lg"/></span></a> | - |
| 05  | Visualising categorical data     | <a id="W2L5YT"><span style="color: red;"><i class="fab fa-youtube fa-lg" /></span></a> | <a id="W2L5MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"/></span></a> | <a id="W2L5S"><span style="color: #4b5357;"><i class="fas fa-desktop fa-lg"/></span></a> | - |
| 06  | AE: StarWars + Dataviz | <a id="W2L6YT"><span style="color: red;"><i class="fab fa-youtube fa-lg" /></span></a> | <a id="W2L6MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"/></span></a> | - | <li><a href="/errata#W206">Errata</a></li> <li><a id="AE3">AE3. Repository</a></li> |

-->

<!--
| <div style="width:50px"></div>  | <div style="width:420px"></div>  |  <div style="width:200px"></div> |
|:---:|:---|:---:|
-->

{{% notice warning %}}
The reading list for this week is currently under construction.
{{% /notice %}}

<!-- NOTE: uncomment the following 7 lines to recreate the table -->
<!-- |    |    |    |
|:--:|:---|:--:|
| <i class="fas fa-book"></i> | R4DS: <a id="R4DS3">Chp 3 - Data visualisation</a> | **Required** |
| <i class="fas fa-book"></i> | Data Visualization: <a id="DV3">Chp 3 - Make a plot</a> | **Required** |
| <i class="fab fa-readme"></i> | <a id="LayeredGG">A Layered Grammar of Graphics</a> | Optional |
| <span style="color: red;"><i class="fab fa-youtube fa-lg" /></span> | <a id = "YT_BBC_Joy">BBC: The Joy of Stats</a> | Optional |
| <span style="color: red;"><i class="fab fa-youtube fa-lg" /></span> | <a id = "YT_TedEd_Missrepresentation">TedEd: How to spot a misleading graph</a> | Optional | -->


<!--| <i class="fas fa-chart-bar"></i> | <a id="wealth">Wealth Shown to Scale</a> | Optional |-->
<!--| <i class="fas fa-chart-bar"></i> | <a id="COVIDvis">COVID-19 Data Visualisations</a> | Optional |-->
<!--| <i class="fas fa-chart-bar"></i> | <a id="COVIDsymptom">COVID-19 Search Trends</a> | Optional |-->


## Workshop

<p style="text-align: left"> The lab sheet can be accessed the day before the workshop, and the solutions the day after the workshop.</p>


<!--
| <div style="width:300px;text-align:left">Laboratory Title</div> | <div style="width:170px;text-align:left">Links</div> | <div style="width:180px;text-align:left">Date</div> |--->
| <div style="text-align:left">Laboratory Title</div> | <div style="text-align:left">Links</div> | <div style="text-align:left">Date</div> |
|:---|:---|:---|
| Lab03: TBD | <li><a id="LAB3I">Instructions</a></li> <li><a id="LAB3R">Repository</a></li><li><a id="LAB3K">Solutions</a>(<a id="LAB3Kraw">Raw</a>)</li> | Fri, 11 Oct |


## In-class test

<span><p style="text-align: left"> The in-class test (`inclass-test-A`) will take place this week, during the Wednesday lecture. You can find more information about the assignment <a id="inclasstest">here</a>.</p></span>

<!-- ## Assignment

<span><p style="text-align: left"> The first homework assignment (`hw-01`) is due by the end of this week. You will find more information about the assignment <a id="homework">here</a>.</p></span>

<p style="text-align: left">If you are having difficulty accessing your homework or lab repository, see troubleshooting advice <a id="troubleshoot">here</a>.</p>
 -->

<!--
## Assignments

<p style="text-align: left">If you are having difficulty accessing your HW or Lab repo, see troubleshooting advice <a id="troubleshoot2">here</a>.</p>

| <div style="width:300px;text-align:left">Assignment Title</div> | <div style="width:170px;text-align:left">Links</div> | <div style="width:180px;text-align:left">Due</div> |
|:---|:---|:---|
| HW01: Data visualisation | <li><a id="HW1I">Instructions</a></li> <li><a id="HW1R">Repository</a></li><li><a id="HW1K">Solutions</a>(<a id="HW1Kraw">Raw</a>)</li> | Fri, 07 Oct, 12:00 UK (Wk 3) |
| OQ01: Data visualization | <li><a id="OQ1">Quiz</a></li> | Mon, 03 Oct, 12:00 UK |


## Code-along

<p style="text-align: left"> Recordings and files from Thursday's code-along.</p>
  
  | <div style="width:200px"></div>  | <div style="width:480px"></div>  |
  |:---|:---|
  | Recording | <a id="CA2YT"><span style="color: red;"><i class="fab fa-youtube fa-lg"> </i></span></a> <a id="CA2MH"><span style="color: #0A1E3F;"><i class="fas fa-file-video fa-lg"></i></span></a>
  | Session artifacts | <a id="CA2Rmd">.Rmd</a> <a id="CA2Md">.md</a>|
  -->

<!--  
  ## Interactive R tutorials
  
  <p style="text-align: left"> The following extras are designed to give you more practice with R. If you're struggling with any of the topics covered this week, we strongly recommend you work through these.</p>
-->

<!--
<p style="text-align: left"> The following are interactive R tutorials, designed to give you more practice with R. These are optional, but the “Airbnb Listings in Edinburgh” dataset shows up in your next homework assignment as well, so you might want to go through that one so that you can gain familiarity with it. If you’re struggling with any of the topics covered this week, we strongly recommend you work through the second tutorial as well.</p>
-->

<!--
|  <div style="width:480px"></div>  |  <div style="width:200px"></div>  |
|:---|:---|
| <a id="RT1">Data Visualization Basics</a> | Extra practice |
| <a id="AE2">Application exercise 2 - Star Wars</a> | Help: <a id="OpeningaProject">Opening a Project</a> |
| <a id="RT2">Airbnb Listings in Edinburgh</a> | Extra practice | -->



