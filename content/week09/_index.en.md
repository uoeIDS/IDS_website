---
chapter: true
pre: "<b>9. </b>"
title: "9. Classification and Model Building"
menuTitle: "Classification and Model Building"
weight: 9
tags: ["week 9", "tasks", "videos", "assignments", "readings", "code-along", "tutorials"] 
description: "Week 9 (15 Nov 2021 - 21 Nov 2021): Logistic regression for predicting categorical data and model building."

hidden: false
---

# Classification and Model Building

_Week 9 (15 Nov 2021 - 21 Nov 2021)_

Logistic regression for predicting categorical data and model building.

## Tasks

<ol>
  <li>Watch the <a href="#videos">Videos</a>.</li>
  <li>Do the <a href="#readings">Readings</a>.</li>
  <li>Complete the <a href="#assignments">Assignments</a>.</li>
  <li>(Optional) Complete the <a id="PE03">Peer Evaluation</a>.</li>
</ol>

## Videos

<p style="text-align: left">You have two options for watching the course videos, on YouTube or on MediaHopper. You can also find a playlists for all course videos on YouTube <a id="playlistyt">here</a> and on MediaHopper <a id="playlistmh">here</a>.

| <div style="width:50px;text-align:center">No.</div> | <div style="width:250px;text-align:left">Title</div> | <div style="width:80px;text-align:center">YouTube</div> | <div style="width:100px;text-align:center">MediaHopper</div> |  <div style="width:80px;text-align:center">Slides</div> | <div style="width:170px;text-align:center">Additional Links</div> | 
|:---:|:---------------------|:-------:|:-----------:|:--------:|:------|
| 01  | Keeping up with IDS: Week 9| <a id="W9L1YT"><span style="color: red;"><i class="fa fa-youtube-play" aria-hidden="true" /></span></a> | <a id="W9L1MH"><span style="color: #0A1E3F;"><i class="fa fa-file-video-o" aria-hidden="true"/></span></a> | - | - |
| 02  | 	Logistic regression | <a id="W9L2YT"><span style="color: red;"><i class="fa fa-youtube-play" aria-hidden="true" /></span></a> | <a id="W9L2MH"><span style="color: #0A1E3F;"><i class="fa fa-file-video-o" aria-hidden="true"/></span></a> | <a id="W9L2S"><span style="color: #4b5357;"><i class="fa fa-desktop" aria-hidden="true"/></span></a>  | - |
| 03  | 	Prediction and overfitting  | <a id="W9L3YT"><span style="color: red;"><i class="fa fa-youtube-play" aria-hidden="true" /></span></a> | <a id="W9L3MH"><span style="color: #0A1E3F;"><i class="fa fa-file-video-o" aria-hidden="true"/></span></a> | <a id="W9L3S"><span style="color: #4b5357;"><i class="fa fa-desktop" aria-hidden="true"/></span></a>  | - |
| 04  | 	Feature engineering    | <a id="W9L4YT"><span style="color: red;"><i class="fa fa-youtube-play" aria-hidden="true" /></span></a> | <a id="W9L4MH"><span style="color: #0A1E3F;"><i class="fa fa-file-video-o" aria-hidden="true"/></span></a> | <a id="W9L4S"><span style="color: #4b5357;"><i class="fa fa-desktop" aria-hidden="true"/></span></a>  | - |

## Assignments

<p style="text-align: left">If you are having difficulty accessing your HW or Lab repo, see troubleshooting advice <a id="troubleshoot">here</a>.</p>

| <div style="width:300px;text-align:left">Assignment Title</div> | <div style="width:170px;text-align:left">Links</div> | <div style="width:180px;text-align:left">Due</div> |
|:---|:---|:---|
| *Due this week* | | |
| Lab06: Course evaluations | <li><a id="LAB6I">Instructions</a></li> <li><a id="LAB6R">Repository</a></li> | Tue, 16 Nov, 16:00 UK  |
| OQ07: Simple Linear Regression | <li><a id="OQ7">Quiz</a></li> | Wed, 17 Nov, 23:59 UK |
| *Due next week* | | | 
| Lab07: Work on projects | <li><a id="LAB7I">Instructions</a></li> | Tue, 23 Nov, 16:00 UK |
| OQ08: Multiple regression | <li><a id="OQ8">Quiz</a></li> | Wed, 24 Nov, 23:59 UK |
| HW04: Potpourri | <li><a id="HW4I">Instructions</a></li><li><a id="HW4R">Repository</a></li> | Thu, 25 Nov, 16:00 UK | 

## Readings

| <div style="width:50px"></div>  | <div style="width:420px"></div>  |  <div style="width:200px"></div> |
|:---:|:---|:---:|
| <i class="fa fa-book" aria-hidden="true"></i> | IMS: <a id="IMS9">Chp 9 - Logistic regression</a> | **Required** |
| <svg aria-hidden="true" role="img" viewBox="0 0 576 512" style="height:1em;width:1.12em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;position:relative;"><path d="M528.3 46.5H388.5c-48.1 0-89.9 33.3-100.4 80.3-10.6-47-52.3-80.3-100.4-80.3H48c-26.5 0-48 21.5-48 48v245.8c0 26.5 21.5 48 48 48h89.7c102.2 0 132.7 24.4 147.3 75 .7 2.8 5.2 2.8 6 0 14.7-50.6 45.2-75 147.3-75H528c26.5 0 48-21.5 48-48V94.6c0-26.4-21.3-47.9-47.7-48.1zM242 311.9c0 1.9-1.5 3.5-3.5 3.5H78.2c-1.9 0-3.5-1.5-3.5-3.5V289c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H78.2c-1.9 0-3.5-1.5-3.5-3.5v-22.9c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5V251zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H78.2c-1.9 0-3.5-1.5-3.5-3.5v-22.9c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm259.3 121.7c0 1.9-1.5 3.5-3.5 3.5H337.5c-1.9 0-3.5-1.5-3.5-3.5v-22.9c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H337.5c-1.9 0-3.5-1.5-3.5-3.5V228c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H337.5c-1.9 0-3.5-1.5-3.5-3.5v-22.8c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5V190z"/></svg> | tidymodels: <a id="TMBaM">Build a model</a> | Optional |
| <svg aria-hidden="true" role="img" viewBox="0 0 576 512" style="height:1em;width:1.12em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;position:relative;"><path d="M528.3 46.5H388.5c-48.1 0-89.9 33.3-100.4 80.3-10.6-47-52.3-80.3-100.4-80.3H48c-26.5 0-48 21.5-48 48v245.8c0 26.5 21.5 48 48 48h89.7c102.2 0 132.7 24.4 147.3 75 .7 2.8 5.2 2.8 6 0 14.7-50.6 45.2-75 147.3-75H528c26.5 0 48-21.5 48-48V94.6c0-26.4-21.3-47.9-47.7-48.1zM242 311.9c0 1.9-1.5 3.5-3.5 3.5H78.2c-1.9 0-3.5-1.5-3.5-3.5V289c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H78.2c-1.9 0-3.5-1.5-3.5-3.5v-22.9c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5V251zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H78.2c-1.9 0-3.5-1.5-3.5-3.5v-22.9c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm259.3 121.7c0 1.9-1.5 3.5-3.5 3.5H337.5c-1.9 0-3.5-1.5-3.5-3.5v-22.9c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H337.5c-1.9 0-3.5-1.5-3.5-3.5V228c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5v22.9zm0-60.9c0 1.9-1.5 3.5-3.5 3.5H337.5c-1.9 0-3.5-1.5-3.5-3.5v-22.8c0-1.9 1.5-3.5 3.5-3.5h160.4c1.9 0 3.5 1.5 3.5 3.5V190z"/></svg> | tidymodels: <a id="TMP">Preprocess your data with recipes</a> | Optional |

## Code-along


<p style="text-align: left"> Recordings and files from Thursday's code-along.</p>

| <div style="width:200px"></div>  | <div style="width:480px"></div>  |
|:---|:---|
| Recording | <a id="CA9YT"><span style="color: red;"><i class="fa fa-youtube-play" aria-hidden="true"> </i></span></a> <a id="CA9MH"><span style="color: #0A1E3F;"><i class="fa fa-file-video-o" aria-hidden="true"></i></span></a> 
| Session artifacts | <a id="CA9Rmd">.Rmd</a> <a id="CA9Md">.md</a>|

## Interactive R tutorials

<p style="text-align: left"> No interactive R tutorials this week. Use the time to work on projects!</p>