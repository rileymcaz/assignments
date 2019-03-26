## Homework Assignment 4 - Experiments

Version History: 

- Released 2019/3/26

This assignment is due Friday April 5, 8 PM.

Create your homework repository in github classroom:
[https://classroom.github.com/a/rPJoRgHV](https://classroom.github.com/a/rPJoRgHV).
At the time of submission, it should contain one PDF file named
`HA4-LastNameFirstName.pdf.`You may include other files, e.g., a file
downloaded from Google Sheets, as supplementary material.

In your PDF, please complete the following problems below. Each problem will
specify what should be shown. If your solution requires multiple calculations
and you are using a spread sheet or other program to help, please clearly
label what is going on in each step in a way that can be seen without
interacting with the program. 

Example 1: If you use a spreadsheet, each sub-result should have a label
next to it explaining what the sub-result is and how it was calculated,
visible from the PDF, even if you include the spreadsheet file. I should not
have to open the spreadsheet file to see what it is. 

Example 2: If you use a script, each sub-result should have a comment above it
explaining what it is and what the code does to generate it.


### Section A: Experiment Design

For each of the scenarios A.1 and A.2, describe an experiment that tests the
idea in question. Describe:

- the conditions of the experiment and the criteria for success
- independent variables, dependent variables, control variables, random
  variables, and confounding factors as well as your justification/explanation 
  for each of them 
- the population, how participants would be drawn from it, how many would
  participate, and how they would be assigned to trials
- the type of tasks the participants would perform, where the differences
  in trials would arise from (e.g., what changes in data?), and what order the
  trials would be given in
- your data analysis procedure including whether you would prune data points
  (and why) and what statistical tests you would use to analyze the collected
  data (and why)
- the limitations of your study, why may it not apply to someone else's
  similar problem?

If there are multiple possible criteria / interpretations to the scenario,
choose one that you think is among the most important, describe what it is,
explain why it is important, and design the rest of the experience (e.g.,
tasks, variables) with that particular criteria / interpretation in mind.

In some cases, your answer may be dependent on information you do not know but
could discover in piloting. In those cases, note where you would pilot and
what you would determine from the pilot for your answer.

The Lecture 18 slides list statistical tests that can be used for greater than
two conditions.

#### A.1 Smart Watch Text Size

What is a good default text size for notifications on a smart watch?


#### A.2 Tutorials

Suppose you're working on social media app at a mid-size start up. Your app currently
drops users into a tutorial as soon as they sign up, but your coworkers are
considering replacing it with a single signifier as to where the tutorial is
located so savvy users can start posting right away. Does either design result
in more people making their first post?


#### A.3 Number of Participants

Suppose you are planning a within subjects study to check if there is a
difference between the time to order lunch using your interface versus that of
an existing interface. You know the existing interface has an average time of
142 seconds with a standard deviation of 21 seconds and that ordering time is
normally distributed. You consider a difference in order time of 20%
meaningful. How many participants do you need for your experiment assuming the
commonly accepted level of significance and power? How many participants would
you need if a difference of 10% was meaningful?

You may calculate this yourself or use a tool (including online). If you
calculate this by hand, include any reference material you used and describe
each step in the calculation. If you use a tool, explain why you chose the
tool, what settings you used, and why. Include screenshots. Also, include the
URL if the tool is online. In either case, if you had guidance (e.g.,
StackOverflow post), cite that guidance.


### Section B: "By-Hand" Statistical Tests

In the problems in this section, you will either perform a statistical test
appropriate to the scenario to determine if the described experiment has a
statistically significant result or compute statistical estimates. Please show
your work similar to what we did in class where sub-results such as the (when
applicable) test you chose, sample means, sample standard deviations,
evidence/argument of meeting test assumptions, differences and sums of
differences, observed and expected outcomes, degrees of freedom, standard
error or standard deviation, final test statistic, and p-value are shown. 

You may use an existing tool to calculate the sample mean and sample standard
deviation (if required), as well as perform any basic arithmetic operation
(addition, subtraction, multiplication, division, square root, etc.) 

**You may not use a tool geared towards doing the entire statistical test for
you.** You may however verify your result using a program that performs the
test directly. If you do so, please include what commands you used to verify
and what your result was. If you choose to do this, you must still include the
sub-results as described above. Note that we are using the Student's t test
for both paired and independent unequal variance samples. The latter is often
replaced by the Welch's t test in practice, and thus stats programs may
perform the latter. You may choose to do the latter by hand when applicable
but if you do so, please make it clear.

The experiments and data described in this section are fictional and for
educational purposes only. 

#### B.1 Mobile Text Entry

A cell phone vendor runs an experiment to compare entering text through an on
screen keyboard (with word suggestions). In the experiment, 18 participants
were asked to input a (randomly generated) block of text using standard input
and path input. The order of trials was randomly set per participant. Through
a series of tasks, the participants' words per minute text entry speed were
measured as:

Standard: [33.8, 27.0, 29.9, 36.2, 32.3, 20.1, 29.8, 14.2, 24.5, 18.1, 25.7, 32.3, 26.8, 25.6, 22.2, 18.7, 32.5, 24.0] 

Path Input: [32.5, 23.2, 19.6, 35.2, 36.9, 24.1, 48.2, 18.4, 30.4, 28.5, 42.3, 41.8, 31.2, 33.0, 22.9, 14.2, 27.2, 31.3]

Is there a significant difference in text entry speed between the two? 

#### B.2 Product Search

An online store runs an experiment to compare how quickly people can a
specific product, given its attributes (e.g., color, size, brand), on their
website. With a group of 50 participants, 25 were randomly assigned an
interface where the search results would automatically update on changing any
attribute parameter and the other 25 were shown an interface where it would
only update when clicking a specifically marked search button. The measured
times (in seconds) were as follows:

Automatic Update: [56.1, 55.8, 41.5, 42.3, 35.6, 32.2, 29.6, 62.6, 40.4, 41.1, 33.7, 52.0, 30.5, 43.1, 36.9, 48.5, 40.4, 34.4, 44.7, 48.9, 45.6, 47.7, 39.3, 41.7, 38.9]

Search Button: [33.6, 31.7, 28.1, 35.7, 33.4, 28.5, 36.9, 31.4, 35.2, 37.9, 45.5, 39.6, 30.1, 36.6, 32.3, 31.5, 32.7, 33.8, 35.2, 40.3, 38.6, 36.9, 28.9, 41.0, 42.6]

Is there a significant difference in search speed?

### B.3 Email Redesign

An online email service is re-designing its site. When a user logs in, they
will be offered a tour of the new design. The service wants to know which of
two welcome screens, one shaped like a speech bubble and the other a simple
rectangle, results in more people starting the tour. The service randomly
selects 600 users and shows them the re-design early. Of the users, 300 get
the speech bubble and the rest the rectangle. In post-processing the data, a
few users were removed because they spent less than a second on the site. The
data kept indicated that 36 people started the tour of the 298 people who saw
the speech bubble and 22 people started the tour of the 294 people who saw the
rectangle.

Is there a significant difference in reaction to the two welcome screens?


### B.4 Navigation

An experiment measured how many basic interactions (clicks, moves, etc) are
fired when trying to find a particular feature across three three menu
designs: Double Tab, Fly Out, and Trail. The tasks were completed by 18, 19,
and 22 participants respectively. The following average interaction counts
(across trials) were recorded:

Double Tab: [95.0, 71.9, 56.8, 92.9, 68.1, 93.8, 75.5, 88.6, 78.1, 84.0, 68.4, 105.4, 77.2, 81.8, 107.0, 52.1, 53.4, 91.5]

Fly Out: [65.2, 115.1, 77.4, 72.0, 114.8, 107.7, 113.9, 98.5, 72.2, 116.6, 81.7, 98.8, 99.2, 81.5, 93.8, 98.8, 90.0, 66.4, 88.8]

Trail: [133.9, 91.4, 102.9, 96.9, 144.8, 120.1, 114.6, 89.8, 117.3, 91.8, 106.7, 92.6, 120.2, 118.1, 101.6, 114.3, 83.0, 74.7, 115.2, 109.5, 119.3, 156.0]


What are the confidence intervals of the conditions (in interval format)?

Plot the confidence intervals.

What can be inferred from these intervals?
