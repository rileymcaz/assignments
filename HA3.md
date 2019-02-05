## Homework Assignment 2

Version History: 

- 2019/02/05: Released

In this assignment, we are exercising:

- Improving an interface to adhere to design principles
- Getting more practice GUI programming in HTML/CSS/Javascript
- Getting more practice with the MVC design pattern

This assignment is based on an assignment from CSC 210 in Fall 2018, which was
also about GUI programming (in Java) and OO design patterns. 

Neither assignment is about UI design. For this assignment, we iterate on the
UI from HA2 using suggestions from class in accordance with design pricniples.
You may start from your HA2 submission or you may start from a sample
solution available through Piazza.

Do not use any Javascript libraries. The HTML, Javascript, and CSS should be
in separate files. No style information should be in the HTML tags. Do not use
HTML tags like `<center>`, `<b>`, or `<i>` to alter visual appearance.
Programmatically added SVG elements may have style attributes.

Use the following link to create your github repository for this assignment:
[https://classroom.github.com/a/WMK7ni6g](https://classroom.github.com/a/WMK7ni6g)
Your submission git repository should contain one HTML file named `HA3.html`
as well as a CSS file `HA3.css`, a JS file `HA3.js`, and a plain text file
`README.txt`.

The webpage should consist of a set of controls and a grid drawing area. The
title of the webpage should be "Last Name, First Name - HA3" where your last
name and first name are used.

The `README.txt` file should contain the rationale for your design decisions
as well as any elaboration on specific design principles as noted below.

**Please note: I may share screen shots or movies of your HA3 and explain how
you chose to design the solution with the class. The focus would be on
positive elements of the design, not on functionality. Please let me know if
you are uncomfortable with your assignment being shown or if you wish for it
to be anonymized.**

### Previous Functionality

The functionality from the previous homework assignment should be preserved.
The user should be able to create a grid of the size of their choosing. The
user should be able to create fish or sharks in a given cell with either a
left or right motion. The user should be able to advance time. 

### Improving Input

In class, we discussed several ways we could improve over the `input
type=text` field currently used for user-input. These included (but are not
limited to):

- Creating separate labeled text fields for each part of the command
- Replacing the text fields with another control such as a drop down
- Adding guides to the grid
- Letting the users click on grid cells to add fish

Design and implement a new interface for this input. In your `README.txt`,
include a *design rationale* where you explain why you chose the design you
did. Your rationale should appeal to the design principles you're fulfilling
and explain any reasons/trade-offs for the design principles you are
violating. A good rationale will also discuss alternative designs and explain
why you chose your design over the alternatives.

Your new design may use elements of the old design, but they should be
justified.


### Prescribed Changes for Particular Design Principles


#### Permit Easy Reversal of Actions

The user should be able to undo previous operations including advancing time,
adding fish, and changing the grid.

In your `README.txt`, you should explain how you have fulfilled the design
principle of `Permit easy reversal of actions.`


#### Help Users Recognize, Diagnose, and Recover from Errors

In HA2, user errors resulted in nothing happening. Change your design to
fulfill this design principle. Explain in your `README.txt` how you have
fulfilled this design principle and what other factors or design principles
led to your particular design choices for this change.

#### Help and Documentation

In HA2, there was no help or documention. Change your design to fulfill the
this design principle. Explain in your `README.txt` how you have fulfilled this
design principle and what other factors or design principles led to your
particular design choices for this change.


### Other Changes

If you want to make other changes to the design, please document what you made
and why you made them. For example, in a previous semester, the assignment was
a simple shape drawing program. A student change the background to dark
claiming it made the difference between the drawing area and the non-drawing
area more clear than the border used in the previous assignment.


#### Defaults

When the page loads, there should be no grid displayed. Any containing
elements, such as a div which isn't visible, may be used.


### Organization

Your Javascript code should demonstrate the Model-View-Controller pattern as
we went over in lecture. 

The application data should be kept by the Model which notifies any Views upon
change.

Any changes to the DOM should be managed by the View. 

The Controller should act as the mediator, making changes to the model as
notified by the View. The Controller does not modify the View.

