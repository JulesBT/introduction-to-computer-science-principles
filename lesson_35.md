<!--- REVISED -->
# Lesson 3.5: Customization II

## Learning Objectives

Students will be able to...

-   Build custom reporter and predicate blocks in SNAP

## Materials/Preparation

-   [Lab 3.5 handout](lab_35.md) (If My Calculations Are Correct...) ([Download in Word](Unit 3 Word/Lab 3.5 If My Calculations Are Correct.docx)) ([Link to PDF](https://teals.sharepoint.com/curriculum/_layouts/15/guestaccess.aspx?guestaccesstoken=BKutmPhPYHFHyejuzJOMtUqlof3QLpHofIy3b0oTbyA%3d&docid=03cba66e93c6c4da1897aac268c1a6d99))

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 10 minutes | Lecture and introduce activity                |
| 25 minutes | Custom reporter activity                      |
| 15 minutes | Debrief and wrap-up                           |

## Instructor's Notes

* [BJC Lecture 9: Recusion](https://www.youtube.com/watch?v=JKn3nsfzBdA)
 - Movie “Inception” as an example of recursion 0:00-0:50
 - Recursion 0:50-1:40
 - Recursion Demo in Snap 1:40-17:00
 - Overview 17:00-21:00
 - Definition of Recursion 21:00-24:30
 - Examples of Recursion (You Already Know It!) 24:30-26:20
 - Trust the Recursion 26:22-29:40
 - Summary of Recursion 29:40-End



1.  Lecture
    1.  Introduce reporter blocks
        -   Ask students to find blocks with the reporter shape (round) and speculate as to what they do
            -   Point out familiar examples, such as ![](xposition.png), ![](answer.png), ![](pickrandom.png), etc.
        -   Explain the concept of reporting (returning) a value, and how reporter blocks are used to provide values to commands
        -   Emphasize that reporters do not (and should not) perform any action—they are used to compute values which are in turn used by commands
    2.  Introduce predicate blocks as a special case of reporter blocks
        -   Emphasize that predicates must return true or false
            -   Be aware, but don't necessarily tell students, that SNAP does not enforce this
        -   Point out examples, such as ![](touching.png), ![](lessThan.png), ![](and.png)
        -   Ask students why it might be useful to differentiate predicates from other reporters
            -   Only predicates can be used in a conditional
2.  Activity
    -   Students should complete the ["If My Calculations Are Correct..."](lab_34.md) activity individually.
        -   This lab consists of a series of independent custom blocks.  The blocks need not necessarily be completed in the order given.
        -   Work with students to ensure they are testing their blocks properly and reporting correct values.
        -   Part 2.2 is challenging and requires traversing a String.
3.  Debrief
    -   Ask a different student to provide their solution to each part.  If time permits, go over multiple students' work for each part.
        -   Point out differences and discuss advantages and disadvantages to different approaches.
        -   Emphasize that custom blocks do not have to be long and complicated to be useful.

## Accommodations/Differentiation

-   Struggling students should focus on just the first 2 or 3 parts of the lab.  Even if they cannot move on to the more difficult problems, getting used to defining custom reporters is helpful and important.
-   Advanced students who finish quickly can be utilized to assist other students.
-   Students who struggle in math may not be familiar with the distance formula used in part 2.1.  Help students to translate the math into SNAP code, but understanding the formula and its applications is not necessary for the activity.
    -   If most students are not equipped to handle this math, a simpler computation, such as area of a triangle or average of three numbers, can be substituted.
