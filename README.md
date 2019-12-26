
# Modern Olympic Games Analysis

## Introduction

<center><img src='Olympic_Rings.gif'>

## Objectives

Throughout this project we will aim to answer the following questions, as divided into the following notebooks:

1. Introduction
    * How can we scrub and prepare our data for further analysis?
    
2. Gender
    * What is the overall gender composition of the Olympic Games?
    * Are height, weight, and age of male and female athletes substantially different?
    * How has the proportion of male and female athletes changed over time?
    * Which countries boast the greatest gender equality based on female participation?
    * Can we predict an athlete's gender based on their height, weight, and age?
    
3. Types of Athletes
    * Which sports have had the most athletes over time?
    * How do the average age, height, and weight differ for athletes of each sport?
    * What trends exist in the height-weight correlation and BMI for athletes of each sport?
    * Are basketball players' heights significantly greater than other athletes?
    * Are rythmic gymnasts significantly lighter than other athletes?
    
4. Olympic Medalists
    * What are the average characteristics of Olympic medalists?
    * How have the average characteristics of Olympic medalists changed over time?
    * Do characteristics of Olympic medalists differ significantly from non-medalists?
    * Which individuals have received the most medals?
    * Who are our youngest and oldest medalists?
    * Which sports have produced the most medalists over time?
    
5. Exploring Countries
    * How do we account for countries with multiple NOC codes throughout history?
    * Which countries have won the most Olympic medals total?
    * Which countries have the highest proportion of athletes winning medals?
    * How can we visualize medal data for each country with plotly choropleth maps?
    * How has the number of participating countries changed over time?
    * How has the number of athletes from our top participating countries changed over time?

6. Seasonal Athletes
    * Is there a significant height difference between summer and winter athletes?
    * Is there a significant weight difference between summer and winter athletes?
    * Is there a significant age difference between summer and winter athletes?
    
7. Trends Over Time
    * How have athlete age, height, and weight changed over time?
    * How has country participation changed over time?
    * Which countries have participated in the highest number of Olympic Games?
    * Which countries have participated in the highest number of summer and winter Olympic Games?
    * How has the overall size of the Olympic Games changed over time?

### Final Project Requirements

Congratulations on making it to module 5! It's been a long journey, but we can finally see the light at the end of the tunnel!

<center><img src='end-of-tunnel.gif'>
<strong><em>Actual Footage of you seeing the light at the end of the tunnel</strong></em>
</center>

Now that you've learned everything we have to teach you, it's time to show off and flex your data science muscles with your own **_Capstone Project_**! This project will allow you to showcase everything you've learned as a data scientist to by completing a professional-level data science project of your choosing. This project will be significantly larger than any project you've completed so far, and will be the crown jewel of your portfolio. A strong capstone project is the single most important thing you can do to get the attention of potential employers, so be prepared to put as much effort into this project as possible--the results are **_worth it!_**

<center><img src='milkshake.gif'>
<strong><em>Your <s>milkshake</s> portfolio brings all the <s>boys</s> employers to <s>the yard</s> your inbox! </strong></em>
</center>

Let's take a look at the project requirements.

### Topic requirements
The projects are in a domain of your choosing.  Your project does not have to answer just one question, but may try to answer multiple questions in a domain, or subsequent questions.  (e.g. Now that we know _X_, what's the next question that comes from this?)  When choosing a topic, try to think through the "So what?" of your question.  

* What are the possible outcomes you think you will find? These should be both mutually exclusive and collectively exhaustive. Why do these matter?
* How could a company or individual make use of your findings to benefit them? What about your findings are _actionable_?

You're completely free to choose any project topic that interests you. However, the project scope must be end-to-end, from data sourcing and cleaning all the way through tuning and analysis of your trained model(s).

Make sure to plan in advance for the feasibility of the question in the time allowed--consider the following questions when selecting your project topic:

* What version this question would allow me to find an answer in 2-3 days?
* What version of this question would allow me/motivate me to work on this problem even after completing Flatiron School?

### Technical Requirements

Your project must meet the following technical requirements:

1. **_No Off-The-Shelf Datasets_**. This project is a chance for you to highlight your critical thinking and data gathering skills by finding the perfect dataset to answer your question. If a pre-existing dataset exists that you'd like to use, it is okay to use it in your project. However, you should consider combining it with other existing sources of data, modifying the dataset through feature engineering. The goal here is to showcase your ability to find and work with data, so just grabbing Boston Housing Dataset or the MNIST dataset is out of the question. 

2. **_Strong Data Exploration, with at least 4 relevant data visualizations._** Think of this project as a way for you to showcase your best possible work in every area that matters. There are few skills that impress employers more than the ability to dive into a new dataset and produce engaging visualizations that communicate important information. For this project, anything worth knowing is worth visualizing. Consider all that you have learned, and don't be afraid to dig into more advanced visualization libraries like seaborn to see what you make! You should make use of visualizations whenever possible during this project, not just during the Data Exploration phase--for instance, consider visualizing your confusion matrices rather than just printing them out as text!

3. **_Makes use of Supervised Learning_**. This requirement dovetails with having a well-defined question, because you'll make use of supervised learning to find the answer! It is both acceptable and encouraged to make use of **_Unsupervised Learning_** techniques as needed in your project (for instance, segmentation with clustering algorithms), but the supervised learning should play a central role in answering your question. 

4. **_Explicitly makes use of a Data Science Process such as OSEMN or CRISP-DM_**. This part is fairly straightforward--you should select a Data Science Process to use and then use this to give structure to your project. Each section should be clearly delineated in your Jupyter Notebook.

5. **_A well-defined question, with a well-defined answer._** Your project should clearly state the question you are trying to answer, and provide any background context needed to understand it. For instance, if you are trying to detect faultlines using Earthquake data, you should provide a brief primer on both the topic and your dataset so that the reader can better understand your topic and approach. Similarly, the findings of your project should be clearly communicated. Do not just tell your audience the final accuracy of your models--be sure to answer "big picture" questions as well. For instance--why are these findings important or useful? Would you recommend shipping this model to production, or is more work needed? Who are these findings useful to, and why should they care? **_NOTE:_** Inconclusive results are okay--from a purely scientific perspective, they are no more or less important or valuable than any other kinds of results. If your results are inconclusive, you should discuss what your next steps would be from there. For instance, what do you think it would take to get conclusive results--more data? Different data that was unavailable? Both? 


### Deliverables

The deliverable for this project will be three components:

1. A **Jupyter notebook** for a presentation.  This will end up being the readme on your github. 
  * The Jupyter notebook will have two components:
    1. An **_Abstract_** section that briefly explains your problem, your methodology, and your findings, and business recommendations as a result of your findings. This section should be 1-2 paragraphs long.  
    2. The technical analysis for a data science audience. This detailed technical analysis should explicitly follow a Data Science Process as outlined in the previous section. It should be well-formatted and organized, and should contain all code, visualizations, and detailed explanations/analysis.
2. A **blog post** showcasing your project, with a focus on your methodology and findings. A well-written blog post about your project will probably be the first thing most recruiters and hiring managers will see, so really take the time to polish up this blog post and explain your project, methodology, and findings/business recommendations in a clear, concise manner. This blog post should cover everything important about your project, but remember that your audience for this blog post will largely be non-technical. Your blog post should definitely contain visualizations, code snippets, and anything else you find important, but don't get bogged down trying to explain highly technical concepts. Your blog post should provide a link to the GitHub repo containing your actual project, for people that want to really dive into the technical aspects of your project.
3. A **video walkthrough** of your non-technical presentation. Some common video recording tools used are Zoom, Quicktime, and Nimbus. After you record your presentation, publish it on a service like YouTube or Google Drive, you will need a link to the video to submit your project.


### Final Project Proposals (2 project ideas)

Selecting the right topic and selecting a problem with the appropriate scope can make or break a good project before you even begin. When starting, try to think up at least 2 different project ideas to explore that you can discuss with your instructor. Consider the following questions when coming up with your project. 

#### Project Ideation Questions

1. What question/questions are you trying to solve?
  * What are the outcomes you think you will find (could use mutually exclusive collectively exhaustive for this)? Why do they matter?
  * How would a person or business take action upon learning the results of your project? How will your findings be _useful_?
  * What version this question would allow me to find an answer in 2-3 days?
  * What version of this question would allow me/motivate me to work on this problem even after completing Flatiron School?

2. What are some data sources that would allow you to answer this?
  * What is the ideal data you would hope to gather to answer this question?  
  * Potentially missing data, that could cause omitted variable bias?
4. Is this a classification task? A regression task? Both?
5. What are the challenges or obstacles you foresee with this project?
6. What are your next steps moving forward?

### Example Student Project

To give you a frame of reference, take a look at this amazing [technical report](https://github.com/paulinaczheng/twitter_flu_tracking) from a previous student that used tweet data to predict the weekly number of flu cases during flu season. Pay attention to how well structured the project is, and how much she relies on great visualizations to tell her story for her. Your explanations don't have to be wordy--a visualization is worth a thousand words!

# Summary

The Capstone Project and project review are the most critical part of the program. They give you a chance to both bring together all the skills you've learned into realistic projects and to practice key "business judgement" and communication skills that you otherwise might not get as much practice with. Most importantly, they provide employers with a very strong signal about your technical abilities, and allow you to show the world what an amazing Data Scientist you've become!

The projects are serious and important. They are not graded, but they can be passed and they can be failed. Take the project seriously, put the time in, ask for help from your peers or instructors early and often if you need it, and treat the review as a job interview and you'll do great. We're rooting for you to succeed and we're only going to ask you to take a review again if we believe that you need to. We'll also provide open and honest feedback so you can improve as quickly and efficiently as possible.

We don't expect you to remember all of the terms or to get all of the answers right. If in doubt, be honest. If you don't know something, say so. If you can't remember it, just say so. It's very unusual for someone to complete a project review without being asked a question they're unsure of, we know you might be nervous which may affect your performance. Just be as honest, precise and focused as you can be, and you'll do great!

## Submitting your Project

You’re almost done! In order to submit your project for review, include the following links to your work in the corresponding fields on the right-hand side of Learn.

1. **GitHub Repo:** Now that you’ve completed your project in Jupyter Notebooks, push your work to GitHub and paste that link to the right. (If you need help doing so, review the resources [here](https://docs.google.com/spreadsheets/d/1CNGDhjcQZDRx2sWByd2v-mgUOjy13Cd_hQYVXPuzEDE/edit#gid=0).)
_Reminder: Make sure to also add and commit a pdf of your non-technical presentation to the repository with a file name of presentation.pdf._
2. **Blog Post:** Include a link to your blog post.
3. **Record Walkthrough:** Include a link to your video walkthrough.

Hit "I'm done" to wrap it up. You will receive an email in order to schedule your review with your instructor.
