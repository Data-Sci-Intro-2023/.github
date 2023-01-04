## Welcome to Environmental Data Science - An Introduction (ESS 523A)!

This is a class at Colorado State University taught by Matt Ross, Caitlin Mothes, and Katie Willi. 

## Goals

The broad goal of this course is to make your graduate or undergraduate research easier, more fun, less frustrating, more collaborative, and more supported, while also preparing you for a career that will include data science skills. The more specific goals of this course are to teach students to: 


  1)	Describe the basic code, file, and data management skills required to efficiently and effectively analyze environmental datasets of a range of sizes.

  2)	Apply linear regression, basic machine learning, and trend analysis techniques to reveal patterns in environmental data relevant to their field of study.
  
  3)	Actively distinguish and select appropriate levels of analysis and code complexity to answer the questions they have about their data.

  4)	Publicly share a code portfolio and participate in collaborative coding efforts.

## Preparation

This class is very fun to teach, but the hardest part is that students come to it with wildly different backgrounds. We are hoping that we can level the playing field through our teaching, making it so that everyone leaves the class with significant skills in R. However, we know that many of you have zero experience coding in R and others have many years of experience. This class will move extremly quicly and if you have no or little experience in R, we strongly encourage you to spend some time reviewing the material below which we have ranked by priority. If you can't review this material or don't already have a general understanding of some of it, this course could move too quickly to stay afloat. 

### Required to review before the course starts

- [Stat 158](https://csu-r.github.io/Module1/) - Vectors, data frames, installing R, etc...

- [RStudio Materials](https://education.rstudio.com/learn/beginner/) - A series of
videos, books, and more to get you started in R

- [RStudio Primers](https://education.rstudio.com/learn/beginner/) - Interactive
online coding. Really excellent if you can make it through all of the primers. 


### Tidyverse and more Intro, helpful to review, but we will cover some of this. 

- [R for Data Science](https://r4ds.had.co.nz/introduction.html) - Covers all of
the basic intro material, from a tidyverse perspective. As discussed, this is 
one way to find solutions in R, it happens to be my preferred way, but there are
lots of Base R ways that work just fine! This is a big book, and should be thought
of as a reference!

- [Stat 159](https://csu-r.github.io/Module2/) - A CSU specific course for an
intro to the tidyverse


### Additional Core Introductory Material

- [Happy Git With R](https://happygitwithr.com/) - Phenomenal resource for learning
git, GitHub, and RStudio integration. As discussed, using Git/GitHub/R together
is a really important way to keep workflows open and robust


- [R Markdown](https://bookdown.org/yihui/rmarkdown/#preface) - The primary 
book for learning more about R Markdown and all of its quirks

- [Cheatsheets](https://www.rstudio.com/resources/cheatsheets/) - Short
clear documents that cover so much material from dplyr to shiny apps. Great
for quick references


## Approach and Expectations

This class is flipped, meaning all lectures are delivered on our [YouTube channel](https://www.youtube.com/channel/UCgdZkOZfmrAFHkDHYI5taVw) and you will 
be expected to watch them before class. To encourage this we will have weekly quizzes on lecture content, these quizzes will be helpful for us to see what 
concepts are easier/harder to grasp and how we can best help in class. 

So without lectures in class what do we do together? We code! This class has almost 6 hours of contact time per week, 
and we fully expect you to finish your homework in the class period alloted. The flipped class allows for deeper discussion about the common pitfals of
[coding](https://ieeexplore.ieee.org/document/7344151).  
Generally we will do a quick live-code review of concepts from the videos, but more than 1.5 hours per day will be dedicated to you coding in class.
As such, coming to class is a vital part of how you can be successful and we fully expect you to be there everyday, except for the inevitable 
mitigating circumstances that we all know will arise. 

We also will actively encourage a collaborative coding environment where students help each other, discuss the best approach to solving various coding problems, and deeply engage in online coding help including AI code assistants like GitHub CoPilot or ChatGPT-3. We also hope that outside of class, you will use our Teams channel to discuss code issues!

Each week we will cover new topics, you will submit your code through GitHub, and your peers will grade your code based on a key we share. A full syllabus that we may occasionally update is [here](https://colostate-my.sharepoint.com/:w:/g/personal/ccmothes_colostate_edu/EdQG_l5PZqVNomB2xImV1OoBSEM4bEXJYSwOW_YnxJTU6g?e=pwLcfo) with a schedule below. 

We will always send announcements with assigments, video links, and other updates through canvas. 

| Week | Date (M)         | Content                                                                                                                                                                                                                                                                                                                                                                                               |
| ---- | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0    | Before 1/18/2023 | Class Preparation (i.e., software installation, GitHub account creation, R refresher tutorials)                                                                                                                                                                                                                                                                                                       |
| 1    | 1/18/23          | Introduction to R, RStudio, R Markdown, Git and GitHub; R fundamentals including packages, functions, data types (including spatial), data wrangling with the Tidyverse and visualization with ggplot2.                                                                                                                                                                                               |
| 2    | 1/23/23          | Debugging, final project introduction<br>In this week, we will practice debugging faulty code in a systematic way, including guidance for how to ask the community for help with a focus on reproducible examples. We will also explore how AI coding assistants can help code, and discuss why they may be unethical.                                                                                |
| 3    | 1/30/23          | Iteration, Functions, API calls for data, and data munging (indexing, cleaning, etc...)<br>Using live environmental data from API calls, we will learn how to iterate over a single function call using for and while loops. We will then use this knowledge to better understand how to build functions for repeated operations with a focus on data munging of a broad array of environmental data. |
| 4    | 2/6/23           | Geospatial data analysis and visualization, final project introduction.<br>Exposure to numerous R packages that allow you to access various open-source databases that contain spatial environmental data; manipulation, analysis and visualization of point, line, polygon and raster datasets.                                                                                                      |
| 5    | 2/13/23          | Linear models (and family), parallel processing<br>Simple vs. multiple regression models. Time series, cross-sectional analysis, and panel models. Parallel processing to speed model fitting.                                                                                                                                                                                                        |
| 6    | 2/20/23          | Introduction to Machine Learning, Train, Validate, Test approach, CART, random forest, and gradient boosting<br>Advantages and disadvantages of machine learning, discuss common pitfalls of ML. Introduce three simple methods that are commonly used with environmental data.                                                                                                                       |
| 7    | 2/27/23          | Uncertainty in models, bootstrapping, cross-validation<br>Understanding uncertainty calculations. Calculating confidence intervals using bootstrapping. Out-of-sample testing using cross-validation.                                                                                                                                                                                                 |
| 8    | 03/06/23         | Final projects                                                                                                                                                                                                                                                                                                                                                                                        |
