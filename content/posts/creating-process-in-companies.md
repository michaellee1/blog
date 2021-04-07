---
title: "Creating process in companies"
date: 2021-04-07T00:11:19-04:00
categories: ["Blogpost"]
draft: false
---

This is one of my favorite XKCD comics.  While I think it was meant to discourage unnecessary optimization, I think it really emphasizes the value of internal processes.  

![](https://imgs.xkcd.com/comics/is_it_worth_the_time.png)

I’m of the opinion that whenever you find yourself doing something repetitive, you should think hard about whether making a process to automate that task makes sense.

If you can identify one 5 minute task that you do 5 times each workday and automate it, you will save a **full month of time** over the next few years.  Now multiply this across additional hires as the company expands - this could be enormously beneficial in the long run.

This isn’t even taking to account that figuring out how to automate **is fun**, and usually **replaces a non-fun task**.

## Rules for automation
* Time to implement >>> time saved, **probably by at least 3X**.  People tend to underestimate time to implement and overestimate time saved, and there is always onboarding cost, even for a tiny automation.
* Go for 80/20 rule aggressively here.  You don’t necessarily need to automate the entire task.  Get the best ratio of time to implement vs. time saved.
* Try to solve it yourself.  Don’t rope in people who don’t experience the problem to help you solve this, as this will lead to bloat.
* Create a robust solution.  If your shitty solution takes 2 minutes to figure out every time and breaks every two months then it’s useless.

## We should optimize processes like lines of code
My favorite old-school optimization method for scientific python (each line can take a long time), is using [line_profiler](https://github.com/rkern/line_profiler).  It tells you how long each line takes, so you can optimize only the most impactful parts.

**We should create and optimize processes this way as well.**
* Record how long a task takes in comparison to other tasks.
* Break that task into subtasks and focus automation on the longer parts
* Weigh automation by effectiveness and time to complete.