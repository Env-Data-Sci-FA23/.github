## Welcome to Environmental Data Science - An Introduction (ESS 523A)!

This is a class at Colorado State University taught by Caitlin Mothes, Katie Willi and Matt Ross

M-W-F 8:00am-9:50am, WCNR Building Room 243

## Goals

The broad goal of this course is to make your graduate or undergraduate research easier, more fun, less frustrating, more collaborative, and more supported, while also preparing you for a career that will include data science skills. The more specific goals of this course are to teach students to: 


  1)	Describe the basic code, file, and data management skills required to efficiently and effectively analyze environmental datasets of a range of sizes.

  2)	Apply various analysis techniques to reveal patterns in environmental data relevant to their field of study.
  
  3)	Actively distinguish and select appropriate levels of analysis and code complexity to answer the questions they have about their data.

  4)	Publicly share a code portfolio and participate in collaborative coding efforts.

## Preparation 

### REQUIRED to do before the class starts

#### 1) Set up Instructions and Tutorials

- You **must** install all necesarry software to the computer you will be using in class before the course begins. From the online book [Happy Git and GitHub for the useR](https://happygitwithr.com/github-acct.html), complete **all** of Lessons 4 - 12 (skipping lesson 10, use HTTPS tokens and not SSH), and lessons 13 and/or 14 for troubleshooting if you have any issues. This book is a phenomenal resource for learning git, GitHub, and RStudio integration.

  *Even if you already have R/RStudio installed, please make sure to install the newest versions. At MINIMUM you must have R version 4.1 or greater*

### Suggested

If you are joining this class with minimal R experience, OR need a refresher on some of the fundamentals, we HIGHLY suggest working through some of these resources/tutorials:


- [RStudio Primers](https://posit.cloud/learn/primers) - Interactive
online coding. Really excellent base material and the most useful way to prepare for the course. 

- [Stat 158](https://csu-r.github.io/Module1/) - Vectors, data frames, installing R, etc...

- [RStudio Materials](https://education.rstudio.com/learn/beginner/) - A series of
videos, books, and more to get you started in R.

- [R for Data Science](https://r4ds.had.co.nz/introduction.html) - Covers all of
the basic intro material, from a tidyverse perspective. As discussed, this is 
one way to find solutions in R, it happens to be my preferred way, but there are
lots of Base R ways that work just fine! This is a big book, and should be thought
of as a reference!

- [Stat 159](https://csu-r.github.io/Module2/) - A CSU specific course for an
intro to the tidyverse


#### Additional Core Introductory Material

- [R Markdown](https://bookdown.org/yihui/rmarkdown/#preface) - The primary 
book for learning more about R Markdown and all of its quirks.

- [Cheatsheets](https://www.rstudio.com/resources/cheatsheets/) - Short
clear documents that cover so much material from dplyr to shiny apps. Great
for quick references.


## Approach and Expectations

This class is flipped, meaning any lectures will be delivered on our [YouTube channel](https://www.youtube.com/channel/UCgdZkOZfmrAFHkDHYI5taVw) and you will 
be expected to watch them before class. To encourage this we will have weekly quizzes on lecture content. These quizzes will be helpful for us to see what concepts are easier/harder to grasp and how we can best help in class. 

So without lectures in class what do we do together? We code! This class has almost 6 hours of contact time per week, and such you will likely be able to finish your homework in the class period alloted. The flipped class allows for deeper discussion about the common pitfals of
[coding](https://ieeexplore.ieee.org/document/7344151).  

Generally we will do a quick live-code review of concepts from the videos, but often more than 1.5 hours per day will be dedicated to you coding in class.

As such, coming to class is a vital part of how you can be successful and we fully expect you to be there everyday, except for the inevitable mitigating circumstances that we all know will arise. 

We also will actively encourage a collaborative coding environment where students help each other, discuss the best approach to solving various coding problems, and deeply engage in online coding help including AI code assistants like GitHub CoPilot or ChatGPT-3. We also hope that outside of class, you will use our Teams channel to discuss code issues!

Each week we will cover new topics, you will submit your code through GitHub, and you or your peers will grade your code based on a key we share. A full syllabus that we may occasionally update is [here]([https://colostate-my.sharepoint.com/:w:/g/personal/ccmothes_colostate_edu/EdQG_l5PZqVNomB2xImV1OoBSEM4bEXJYSwOW_YnxJTU6g?e=pwLcfo](https://colostate-my.sharepoint.com/:w:/g/personal/ccmothes_colostate_edu/EfdTUZnB6PtFs19qM88FUJgBRhFQW7IriLrpt69Ai3349A?e=ywjpwJ) with a schedule below. 

We will always send announcements with assigments, video links, and other updates through Canvas. 

A final note. The data science field changes extremely quickly. We will teach you the best way we know how to do things, but these areas change very quickly and we may teach you things that are outdated. For example, over the long term, Quarto is replacing RMarkdown because it is more natively multi-lingual (able to use Python, Julia, etc...), but we are using RMarkdown. Why? Because Rmarkdown is currently more stable, but likely the 2024 version of this class will use Quarto. The differences between these technologies is small, but not zero. A bigger shift we will discuss is how to code with AI assistants, another place where we are hoping to expose you to the cutting-edge resources so you start your career using the best tools available. 

| Week | Date (M)         | Content                                                                                                                                                                                                                                                                                                                                                                                               |
| ---- | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0    | Before 10/16/23 | Class Preparation (i.e., software installation, GitHub account creation, R refresher tutorials).                                                                                                                                                                                                                                                                                                       |
| 1    | 10/16/23          | Using Git and GitHub                                                                                                                                                                                              |
| 2    | 10/23/23          | Debugging<br>In this week, we will practice debugging faulty code in a systematic way, including guidance for how to ask the community for help with a focus on reproducible examples. We will also explore how AI coding assistants can help code, and discuss why they may be unethical.                                                                                |
| 3    | 10/30/23          | API calls for data, functions, iteration, and data munging (indexing, cleaning, etc.).<br>Using live data from API calls, we will learn how to iterate over a single function call using for loops and mapping. We will then use this knowledge to better understand how to build functions for repeated operations with a focus on data munging of a broad array of environmental data. |
| 4    | 11/6/23           | Introduction to geospatial data analysis and visualization.<br>Exposure to numerous R packages that allow you to access various open-source databases that contain spatial environmental data; manipulation, analysis and visualization of point, line, polygon and raster datasets.                                                                                                      |
| 5    | 11/13/23          | Linear models (and family), parallel processing.<br>Simple vs. multiple regression models. Time series, cross-sectional analysis, and panel models. Parallel processing to speed model fitting. |
| 6    | 11/20/23          | **No Classes - Fall Break** |
| 7    | 11/27/23          | Introduction to Machine Learning  |
| 8    | 12/04/23          | Final Projects: R Markdown customization, Bookdown, Quarto, Shiny web applications |
