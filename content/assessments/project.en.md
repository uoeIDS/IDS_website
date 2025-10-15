---
title: "Final Projects"
weight: 4
---

You, as part of a __team__, will be responsible for the completion of an open ended final project for this course, the goal of which is to tackle an “interesting” real life problem using the tools and techniques covered in this class. 

{{% notice tip %}}
Stick to optional interim deadlines.
{{% /notice %}}

## Too Long Didn't Read (TL;DR)
You will pick a dataset, from a dedicated list of data sources given below. From different resources, these data sets are carefully selected to make that step easier for you.
Generally, your goal is to do something reasonable with the selected data set using what you learnt from the course. That is your final project in a nutshell! More specifically, you can think of the following steps as an example (but not limited to)

1. **Data set Selection and Understanding**

- Choose a data set from the given list.
- Familiarize yourself with the data set: What kind of data does it contain? What are the attributes? What kind of questions can this data potentially answer?

2. **Problem Definition**

- Define a clear objective or problem statement. What do you aim to achieve with this data set?
- Do necessary data cleaning if you need; Handle missing values, or incorrect data.
- Optionally, find and join relevant supplementary data that may be useful for your problem statement. <!-- Added -->


3. **Exploratory Data Analysis (EDA)**

- Compute some summary statistics (e.g. mean, standard deviation, etc.) to summarise the key aspects about your data. <!-- Added -->
- Use visualization tools to understand the underlying patterns, relationships, and anomalies of data.
- Identify potential correlations or trends in the data.


4. **Model Selection and Evaluation**

- Based on the problem definition, select an appropriate algorithm or method.
- Implement the model and evaluate the model's performance using appropriate metrics (e.g., accuracy, RMSE, etc.)
- Try to suggest further improvements on the model if your first findings are not satisfactory enough
- If appropriate, comment on any appropriate points of ethical concerns that you identified when doing your data science investigation. <!-- Added -->


5. **Feedback and Summarizing**

- Present the project to your tutor, peers or any other potential audience.
- Gather feedback and make necessary improvements.
- Summarize the methodology, and findings using appropriate charts, plots, or graphs.

## May be too long, but please DO READ

The final project for this class will consist of analysis on a dataset of your own selection from the suggested list of options. You can choose the data based on your interests or based on work in other courses or research projects. The goal of this project is for you to demonstrate proficiency in the techniques we have covered in this class (and beyond, if you like) and apply them to a novel dataset in a meaningful way.

The **goal is not to do an exhaustive data analysis** i.e., do not calculate every statistic and procedure you have learned for every variable, but rather let us know that you are proficient at asking meaningful questions and answering them with results of data analysis, that you are proficient in using R, and that you are proficient at interpreting and presenting the results. Focus on methods that help you begin to answer your research questions. You do not have to apply every statistical procedure we learned. <!-- Added: start--> Ensure that you focus on the data that you are investigating and be cautious against over interpretation. <!-- Added: end --> Also, critique your own methods and provide suggestions for improving your analysis. Issues pertaining to the reliability and validity of your data, and appropriateness of the statistical analysis should be discussed here.

**The project is very open ended**. You should create some kind of compelling visualization(s) of this data in R. There is no limit on what tools or packages you may use, but sticking to packages we learned in class (e.g. `tidyverse`) is advised. You do not need to visualize all of the data at once. 

A single high quality visualization will contribute much more to a good mark than a large number of poor quality visualizations. Also pay attention to your presentation. Neatness, coherency, and clarity will count. All analyses must be done in RStudio, using R. You must also set up and use a GitHub repository to collaborate with your team. 

<!-- Delete Cog -->
<!-- <div align="center"> -->
<!-- <i class="fas fa-solid fa-cog fa-spin fa-2x" style="--fa-animation-duration: 15s;"></i> -->
<!-- </div> -->

### GitHub repository

One member of your team should be responsible for managing the repository of your group project. This team member should clone the <a id="project_template_repo">project template repository</a> from the course GitHub account and add each of the team members as collaborators. Instructions on how to clone a repository, add collaborators and to create a new version control R project can be found in the lab worksheets.

{{% notice warning %}}
The project template repository can be found [HERE](https://github.com/uoeIDS/project_template) <!--<a id="project_template_repo">HERE</a> -->.
<br>
<br>
You must add the course GitHub account (`uoeIDS`) as a collaborator to your GitHub repository, similar to the homework process.  
{{% /notice %}}
<!-- Above 'project_template_repo' link does not work, doing a quick hard-code fix.  -->


It is highly recommended that you regularly _commit_ any changes you have made to your work, and to frequently _pull_ & _push_ these changes with your repository on GitHub. Please be aware of any _merger conflicts_ and try to resolve them (if in doubt, contact your team members on how best to resolve a conflict). If you notice an unusual error message then please seek assistance, either from a tutor in workshops or via an informative post on Piazza.

### Data

In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple relationships can be explored. 

<!-- {{% notice warning %}}
The list of recommended dataset has been temporarily removed while it gets finalized for this academic year.
{{% /notice %}} -->

<!-- Added: start -->

For this, we recommend that you select one of the data sets listed below. Read all of the data descriptions and select **one** that interests you the most:


| ID | Link | Description |
|:---|:-----|:------------|
| 01   | [Link](https://www.opendata.nhs.scot/dataset/weekly-accident-and-emergency-activity-and-waiting-times) | Weekly A&E Activity and Waiting Times, Public Health Scotland |
| 02   | [Link](https://www.opendata.nhs.scot/dataset/scottish-heart-disease-statistics) | Scottish heart disease statistics, Public Health Scotland |
| 03   | [Link](https://www.opendata.nhs.scot/dataset/mental-health-inpatient-activity) | Mental health inpatient activity, Public Health Scotland |
| 04   | [Link](https://www.scottishairquality.scot/data/data-selector) | Data on air pollutants in Scottish cities, Air Quality Scotland |
| 05   | [Link](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) | House Prices, Kaggle |
| 06   | [Link](https://www.ncdc.noaa.gov/cdo-web/search) | Precipitation and temperature measurements, National Centers for Environmental Information |
| 07   | [Link](https://www.gov.uk/government/statistics/offender-management-statistics-quarterly-january-to-march-2023 ) | Prisoner population statistics (England & Wales), GOV.UK |
| 08   | [Link](https://www.oecd.org/en/data/datasets/pisa-2022-database.html), [R package](https://cran.r-project.org/web/packages/learningtower/index.html) | PISA (Programme for International Student Assessment), OECD [download data using using R package] |
| 09   | [Link](https://www.cdc.gov/nchs/nhanes/index.html), [R package](https://cran.r-project.org/web/packages/NHANES/index.html) | NHANES, CDC [download data using using R package] |
| 10   | [Link](https://figshare.com/s/b990722d72a26b5bfead) | Bird morphological measurements, Ecology Letters  |
| 11   | [Link](https://archive.ics.uci.edu/dataset/183/communities+and+crime) | Communities and Crime, UCI  |
<!-- | 05   | [Link](https://ssd.jpl.nasa.gov/tools/sbdb_query.html) | Small-Body Database of asteroids and comets, NASA | -->
<!-- | 08   | [Link](https://www.kaggle.com/datasets/mlandry/formula-e-championship) | Formula E championship data, Kaggle | -->
<!-- | 09   | [Link](https://www.kaggle.com/datasets/gyanprakashkushwaha/laptop-price-prediction-cleaned-dataset ) | Laptop prices, Kaggle | -->

It is advised that you select a data set from the list above. However, feel free to search the internet for alternative data sets. Some suggested online data resources can be found at [Kaggle](https://www.kaggle.com), [Scottish Government](https://statistics.gov.scot/data), [Public Health Scotland](https://www.opendata.nhs.scot/dataset), [UK Government](https://www.gov.uk/), [TidyTuesday](https://github.com/rfordatascience/tidytuesday), [World Bank](https://www.worldbank.org/en/home) and [UCI machine learning repository](https://archive.ics.uci.edu/). The dataset you select should have at least 200 rows and a mix of numerical and categorical variables. **Please check with the course organiser or a lecturer as to whether the data you select is feasible for your project**


<!-- Added: end -->

<!-- Delete -->
<!--
- As such, your dataset must have at least 50 observations and between 10 and 20 variables (exceptions can be made but you must speak with the course teaching team). 
- The variables in the data should include categorical variables, discrete numerical variables, and continuous numerical variables.
- If you are using a dataset that comes in a format that we haven't encountered in class, make sure that you are able to load it into R as this can be tricky depending on the source. 

**If you are having trouble ask for help before it is too late!**

{{% notice warning %}}
DO NOT reuse datasets used in examples, homework assignments, or labs in the class.
{{% /notice %}}

Below are a list of data repositories that might be of interest to browse. You're not limited to these resources, and in fact you're encouraged to venture beyond them. But you might find something interesting and ready to use directly:

-->

<!--
LIST must be updated 

<ul>
  <li><a id="TidyTuesday">TidyTuesday</a></li>
  <li><a id="NHSSOD">NHS Scotland Open Data</a></li>
  <li><a id="SOS">Open access to Scotland's official statistics</a></li>
  <li><a id="UKGov">UK Gov Data</a></li>
  <li><a id="KaggleData">Kaggle datasets</a></li>
  <li><a id="OpenIntroData">OpenIntro datasets</a></li>
  <li><a id="Awesome">Awesome public datasets</a></li>
  <li><a id="YRBSS">Youth Risk Behavior Surveillance System (YRBSS)</a></li>
  <li><a id="HarvardData">Harvard Dataverse</a></li>
  <li><a id="OECD">Organisation for Economic Co-operation and Development (OECD)</a></li>
    <li><a id="UCI">UCI machine learning repository</a></li>
  <li>If you know of others, let me know, and we'll add here...</li>
</ul>

-->

### Deliverables

<!-- 1. Proposal     - discussion with your tutor in the workshop (Week6 - Friday 27 October) -->

1. Check-in     - Discussion with a tutor in the workshop (Week 6 - Friday 24 October and Week 9 - Friday 14 November) <!-- edit -->
1. Presentation    - On Friday 28 November (during your workshop session)
1. Report & Presentation Slides - Due Monday 1 December @ 10:00 GMT
1. Peer Evaluation - Due Monday 1 December @ 10:00 GMT

<!-- Added -->

### Check-in

The two 'check-in' points are not assessed and do not count towards your final grade. A check-in will consist of a discussion with a tutor to receive feedback on your current progress and on your future plans. We highly recommend that you put in some effort into preparing for these check-in discussions so that your check-in discussion runs smoothly and that you receive as much feedback as possible.

**You can add any feedback and suggestions you receive from your tutor for you to refer back to in the future in your project_template *README.md* file**


- **Week 6**: You should demonstrate that you have a basic understanding of the data you have selected and have made initial steps in cleaning, summarising and visualising your data. We will be looking to understand whether you have a clear problem statement and that you have a plan as to how you would explore the data to answer your statement.


- **Week 9**: At this stage, you should be able to demonstrate a reasonable understanding of your data and to make some comments in relation to your problem statement, and thinking carefully about what type of model to use. We will be looking to see if your plans are appropriate and reasonable to be completed within the last two week, and that you have thought carefully about your presentation and report.


**It is important to NOT miss these workshops for the health of your final group project.**

<!-- Delete -->
<!--
#### Proposal

The proposal discussion does not count towards your final grade, but you will receive feedback from the tutors and your peers in the workshop so we highly recommend putting the effort in to do a good job to make sure that you are on the right track. 

- The proposal discussion also gives you a chance to practice presenting data in preparation for the final project presentation.

- You can prepare a slide deck for your discussion if you want. There isn't a limit to how many slides you can use, it should summarize your progress overall. 

- Your optional proposal discussion slide deck can cover:

- Section 1 - Introduction: 

- The introduction should introduce your general research question and your data (where it came from, how it was collected, 
what are the cases, what are the  variables, etc.). 
- You should include the output of `glimpse()` or `skim()` of your data frame in the slides.

- Section 2 - Data analysis plan:
  - The variables in the dataset you will use to answer your question.
  - The comparison groups you will use, if applicable.
  - Very preliminary exploratory data analysis, including some summary statistics.
and maybe also some visualizations, along with some explanation on how they help you learn more about your data. (You can add to these later as you work on your project.)
  - Any statistics that you believe will be useful in answering your question(s). (You can update these later as you work on your project and as we learn more about statistical modelling methods.)
  -  What results from these statistics are needed to support your hypothesized answer?
  
{{% notice warning %}}
Proposal discussion will take place during the workshop in week 6 (27 October). It is important to NOT miss that workshop for the health of your final group project.
{{% /notice %}}

-->

#### Presentation

You will need to prepare a slide deck using the template in the repo. There isn't a limit to how many slides you can use, however there is a time limit (10 minutes/per group in total). You can think of this time as 7 minutes talk + 2 minutes questions by default and prepare yourself based on this time limitation in general. 

Each team member should get a chance to speak during the presentation. Your presentation should not just be an account of everything you tried ("then we did this, then we did this, etc."), instead it **should convey what choices you made, and why, and what you found**.

{{% notice tip %}}
Before you finalize your presentation, make sure your code chunks are turned off (not displaying the code) with `echo = FALSE`.
{{% /notice %}}

Presentation schedule: Presentations will take place during the last workshop of the semester (28 November). All teams will give them as a live presentation in the workshop. During your workshop you will watch presentations from other teams in your workshop and will be able to ask questions at the end. The presentation line-up will be generated randomly, later during the semester.

#### Report

Along with your presentation slides, we want you to provide a brief summary of your project. 

- This can be a markdown (`.md`) or an rmarkdown (`.Rmd`) file, depending on whether you want to include code in your report. 
- The report should be around 1,500 words, not including figures, tables, code chunk parts and references. There will be some flexibility when marking, so no penalty will be applied if the word count is less than 1,500 words + 10% extra, that is 1,650 words at most.

This report should provide information on;

- the dataset you're using, 
- your research question(s), 
- your methodology, 
- and your findings. 

<!-- Following notice box has been moved to be earlier  -->
<!--
{{% notice warning %}}
Your report must also contain a link to the GitHub repository for your project, and you must add the course GitHub page (username: uoeIDS) to this GitHub repository, similar to the homework process.  
{{% /notice %}}  -->


{{% notice tip %}}
To find the word count of your report, ensure that you have your report `.Rmd` file open and in the editor panel (top-left) and then navigate to `Edit > Word Count`. The presented value ignores all text within code chunks. It counts the words that appears in the title, section headings and the main text of your report.
{{% /notice %}}


### Team peer evaluation

You will be asked to fill out a survey where you rate the contribution and teamwork of each team member. 
This will be used to calculate an individual mark for each team member, so that it reflects their contribution to the project. The score calculated by the peer assessment will affect 30% of the mark (multiplicatively). More information on how the final individual mark is calculated can be found [here](https://webpaproject.lboro.ac.uk/WorkedExample).
If you do not complete this peer feedback for all members of your team, you will receive a penalty of 20% off your mark. Note that you will need to provide an explanation for each score, in particular for any score of "No contribution" or "Very poor". Remember that the teaching team will be able to use your project's commit history to assess the accuracy and validity of any strong statements made in the peer assessment.


{{% notice warning %}}
<!-- made edits to warning box -->
**IMPORTANT**: If you are concerned that a member of your team is severely under contributing to your group project, then please contact the course organiser as soon as possible.
<br>
<br>
When completing the peer evaluation, if you are suggesting that an individual did less than 5% of the work ("No contribution" or "Very poor" contribution) then you must provide a justifiable explanation.   

<!-- Reduced percentage from 20% to 10% as there are some groups with 5 members -->
{{% /notice %}}

This survey will be available on WebPA, accessible via the course Learn page (Learn > Assessment > WebPA). 

- The deadline for the peer evaluation is Monday 1st December, @ 10:00 GMT.

## Project Repository structure

This is a template repository for your group project. One of your group members should clone this repository and add the other team members as collaborators. You should also add the `uoeIDS` course GitHub account as a collaborator.

- `/data` -- Save any data you are using for your project in this folder.
- `/img` -- If you choose to incorporate any supplementary images into your report or presentation that are not generated by your code, then you should upload the images to this folder.
- `investigation.Rmd` -- Use this file as the primary location for doing your data science investigation. Here you can develop code and document your findings as part of your exploration. Feel free to create additional `.Rmd` files for different group members or different investigation directions - do what works best for your group. 
- `report.Rmd` -- This file is for the write-up of your group project report, which is to be submitted in week 11. Provided that you are documenting your findings during your investigations, then this should involve copying & pasting material and ensuring that the report flows coherently as if from one unified voice.
- `presentation.Rmd` -- Use this file to create your presentation. You will need to download and install the `xaringan` package that contains all of the R and markdown code that you will need to create and compile the presentation slides. For this, run `install.packages("xaringan")` once on your console. Guidance on using the `xaringan` package for creating a presentation in Rmarkdown can be found at [https://bookdown.org/yihui/rmarkdown/xaringan.html](https://bookdown.org/yihui/rmarkdown/xaringan.html).
- `README.md` -- This document, which outlines the structure of the report. The contents of this file will be rendered on GitHub, and so you can add comments below to keep a track of what  and can be used to keep additional note or task lists.

**See the other details from the project template file when you start working**

### Submission and GitHub repository

You will need to submit your project report to Learn (Learn > Assessment > Gradescope > Final project - team) by Monday 1 December:

* A `.html` version of your report (including a link to the GitHub repository) by 10:00
* A `.html` version of your presentation by 10:00.
* Your team peer evaluation (under peer evaluation on Gradescope) by 1 December at 10:00 at latest.

Only _one_ member of your team should submit the report and presentation to Learn. This person will need to add the other team members from the drop down menu that appears under  _View or edit group_ after uploading the files and viewing the submission. Everyone should submit the peer evaluation individually. 

As explained above, you _must_ also add the course GitHub account (username: uoeIDS) to your team GitHub repository by the time of the deadline. 

We expect your GitHub repository to contain the following folders and files:

* `presentation.Rmd` + `presentation.html`: Your presentation slides
* `report.Rmd` + `report.html`: Your report
* `investigation.Rmd` + `investigation.html`: Your working document for your data science investigation (Note: the work here will not be assessed, it is up to you as to how you use these files to distribute work amongst members and to keep notes about what you find.)
* `README.md`: Your progress discussion notes from the check-in meetings earlier in the semester.
* `/data/*`: Your dataset in csv or RDS format, in the `/data` folder.
* `/img/*`: Any supplementary images for your report/presentation.


{{% notice warning %}}
Style and format does count for this assignment, so please take the time to make sure everything looks good and your data and code are properly formatted.
<br>
<br>
There are also 10pts available for reproducibility and organisation - the marks for this will be based on your GitHub repository so make sure you include this.
{{% /notice %}}

### Tips

- You're working in the same repo as your teammates, so merge conflicts will happen and issues will arise, and that’s fine! Commit and push often, and ask questions when stuck.
- Review the marking guidelines below and ask questions if any of the expectations are unclear.
- Make sure each team member is contributing, both in terms of quality and quantity of contribution (we will be reviewing commits from different team members).
- Set aside time to work together and apart (physically). Scheduling regular group meetings to discuss progress, challenges, and next steps is crucial for progress. 
- When you're done, review the documents on GitHub to make sure you're happy with the final state of your work. Then go get some rest!

**Code:** In your presentation your code should be hidden (`echo = FALSE`) so that your document is neat and easy to read. However, your document should include all your code such that if I re-knit your R Markdown file then I should be able to obtain the results you presented.

{{% notice warning %}}
**Exception:** If you want to highlight something specific about a piece of code, you're welcome to show that portion. 
{{% /notice %}}

**Teamwork:** You are to complete the assignment as a team. All team members are expected to contribute equally to the completion of this assignment and team evaluations will be given at its completion---anyone judged to not have sufficiently contributed to the final product will have their grade penalized. **While different teams members may have different backgrounds and abilities, it is the responsibility of every team member to understand how and why all code and approaches in the assignment work.**

### Marking

Total                          | 100 pts
-------------------------------|--------
Presentation                   | 50 pts
Report ( * )                       | 40 pts
Reproducibility and organization ( * ) | 10 pts

( * ) These two marks are readjusted using the peer evaluation and the webPA formula. 

First the Report and Reproducibility marks are calculated at the team level. The individual mark is then calculated as: `(1-0.30) * (Report + Reproducibility) + 0.30 * individual_webPA_score * (Report + Reproducibility)`, where `0.30` is the webPA weighting (how much it affects the mark multiplicatively, i.e. 30%), and `individual_webPA_score` is calculated by webPA software (see the [worked example](https://webpaproject.lboro.ac.uk/WorkedExample) for further information).
Finally, the Presentation mark is added to this score to obtain the final (individual) mark, out of 100.

### Criteria

- **Content:** What is the quality of research question and/or policy question, and the relevancy of data to that question/those questions?
- **Correctness:** Are statistical procedures carried out and explained correctly?
- **Writing and Presentation:** What is the quality of the statistical presentation, writing, and explanations?
- **Creativity and Critical Thought:** Is the project carefully thought out? Are the limitations carefully considered? Does it appear that time and effort went into the planning and implementation of the project?

### Late work policy

- **There is no late submission / make up for the presentation**. You must be in class on the day of the presentation to get credit for it 
(In case of illness, requirement to self-isolate or similar, special circumstances can be applied for from the university: see the <a id="policies">Policies page</a>).

- Late submissions are not accepted for the written component of the project, but extensions are permitted (up to 4 days).
<!-- The late work accepted for the written component of the project up to 4 days after the deadline, with 5% penalty for each 24 hours late. -->



