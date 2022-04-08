****SENG 637 - Dependability and Reliability of Software Systems****

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:              | 16  |
|------------------------|-----|
| Shahryar Soltanpour    |     |
| Mohammad Reza Kianifar |     |
| Muhammad Raihan        |     |

(Note that some labs require individual reports while others require one report
for each group. Please see each lab document for details.)

# Link of demo video

[Video Link](TODO://add-here-the-link-of-the-video)

It works for everyone with logged-in university account on outlook. Please [tell us](mailto:mohammadreza.kianifa@ucalgary.ca) if you had any problem.

# Introduction

# Assessment Using Reliability Growth Testing 
First, we tried to use the SRTAT tool which has been developed in Dr. Far's laboratory. After converting the input and 
importing that to the software, there were some logical problems that we received errors and the diagram couldn't be 
displayed. 

So we switched to C-SFRAT software. We imported the data and the diagram looked like this:

![img1](./media/report/Imported%20Data.png)

We tried different models to fit the data and 2 of them worked well:
1. Geometric Fit for E, F, and C parameters:
![img2](./media/report/Geometric%20Fit%20-%20C-SFRAT.jpg)

2. Truncated Logistic for E, and F parameters:
![img3](./media/report/Truncated%20Logestic.png)

But we couldn't continue the rest of the project with this tool because it didn't support features like Laplace or 
reliability graphs. So we again switched to use a new tool: CASRE which is a tool that is developed by NASA.

[//]: # (TODO: Doing rest of the parts with CASRE)

# Assessment Using Reliability Demonstration Chart 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed
We used Discord as our communication tool and Zoom for our video calls and also to record the demo. 
Mohammad Reza and Shahryar focused on the RGT and Ammar focused on RDC. Also, Mohammad Reza and Shahryar helped Ammar 
after they did their part. At the end, we double-checked our result and divided the report among our-selves.

# Difficulties encountered, challenges overcome, and lessons learned
This assignment was different from the previous ones because it didn't involved testing tools like unit testing or 
manual testing. Instead, we have to use new tools to fit failure diagram. Learining how to work with these tools and also
finding the tool that contains all of our needs, took plenty of times. Also, we use MacBook as our development system 
but most of these tools work better on Windows. So we had to go to the university to do the project. Meanwhile, we were 
sick, and it was really hard for us to maintain the project and do it before the deadline.

The communication was another challenge that we faced. By using online tools like Discord and Zoom meeting we could 
handle this problem. 

# Comments/feedback on the lab itself
I think the instruction was not accurate for this lab. Because the SRTAT tool is not complete to work with. Also, 
C-SFRAT does not have all the expected outcome. We had to use another tool (CASRE) to to the project. I think it was 
better that this tool was suggested as the main software to work with. 