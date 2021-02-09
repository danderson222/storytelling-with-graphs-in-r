---
title: Storytelling With Your Graphs In R Using ggplot2
author: Dylan Anderson
date: '2021-02-10'
description: "Use text, vertical lines and relevant titles to tell a story of Presidential Approval Ratings in R!"
---

A few weeks ago, I tuned into an [RStudio talk by John Burn-Murdoch](https://blog.rstudio.com/2020/10/16/rstudio-global-2021/) about reporting and visualizing the COVID pandemic. As a data journalist at the Financial Times, he has been extremely influential over the past year creating well-known charts and graphics about the spread of COVID and it's toll on the world. **And it is all because his graphics tell a story**.

As a consultant, I know the importance of storytelling, but doing it in programming is difficult as **the story often gets lost behind the data**. Still, you should always try to tell a story with your graphics, charts and plots, instead of just laying out some numbers and lines on a page. So how do you do this? Well, I had **three main takeaways** from his talk and my experience:

-   **Use text** - it's your secret weapon and can be used in more than just the title

-   **Consider the Emotional and Political Context** - understand how your audience might look at your chart

-   **Use animation intelligently** - animated GIFs, charts and videos are helpful but should be used to underscore points in your story (note I am planning to do a second blog post specifically on this!)

<br>

In this tutorial, I want to explore the `ggplot2` package in R, using functions like `annotate` and `geom_vline` to tell a political tale of Presidential Approval Ratings. I wrote about this before on [Medium](https://dylansjanderson.medium.com/donald-trump-a-stable-president-17306a89d2b5) and on [my website](https://www.policyinnumbers.com/blog/2021/01/26/donald-trump-a-stable-president/) with a more in-depth political analysis.

We will build **5 graphs here**, one combined plot of Presidential Approval Ratings from each president over the past 75 years and four plots of individual Presidential terms with text explaining major events in the presidency.

Check out the ApprovalRatings.Rmd file for the code to do this tutorial!