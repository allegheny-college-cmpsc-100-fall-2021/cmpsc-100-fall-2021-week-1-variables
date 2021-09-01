# Lab: Dig, if you will, some pictures

## Overview

One of the hardest parts of making a space aesthetically pleasing is hanging stuff on the wall. This is doubly so when you want the space between the pictures to be the same given some ideal spacing on a particular wall. In the case of art galleries, this is a particulary recurring issue.

<div class="alert alert-block alert-info">
    <p>This is, of course, a thinly-veiled appeal to you to visit the <b>Faculty Show</b> over in the art gallery in Doane Art. It's a short walk.</p>
</div>

Your job (and, because it's worth grade points) that you choose to accept: your instructor humbly requests a way to calculate how to _evenly space_ various sets of pictures on a wall given ideal "margin" measurements. To wit:

![We get it, Prof., you like your cat.](https://github.com/allegheny-college-cmpsc-100-fall-2021/cmpsc-100-fall-2021-week-1-variables-solution/blob/media/media/boss_gallery.png)

You need to figure out how to appropriately space the three scenarios given in this document _and_ pass three _hidden_ scenarios that take place during grading. You won't see those hidden scenarios, but if you pass the tests given here, you should pass the grader's.

In this lab, you'll practice using:

* `input()`
* various _operators_ (including `=` and the various arithmetic operators)
* Flow of Control (or, Control of Flow)
* Programming in Python
* problem-solving skills

Keep in mind, that you _need four (4) `input()` function statements_ to successfully complete this:

* number of pictures
* width of pictures
* width of wall
* desired margin on either side of pictures

You are, of course, encouraged to work with your table groups to help derive the way to solve this problem. Of course, TLs and your instructor are also available to assist!

### Test scenarios

The following table lists test scenarios for which your program should feature correct outcomes:

|Number of pictures |Width of pictures |Length of wall |Desired margin |Output |
|:------------------|:-----------------|:--------------|:--------------|:------|
|3 |2 |10|1|1.0|
|5 |3 |25|2|1.5|
|4 |10|50|3|1.33|

## Requirements

### Program

* A completed program in the [week-1-lab.py](week-1-lab.py) file
* No remaining `TODO`s
* At least `5` single-line comments
  * Recall, these are the lines with the `#` at the start
* Enough uses of the `input()` function to get required information
* Enough uses of the `int()` function to properly convert the data
* Calculations which involve the `+`, `-`, `*`, or `/` (and their various `+=`) counterparts
  * There are multiple ways to solve this problem, though there is likely one optimal solution, given what we know
* Correct output for hidden scenarios
* Working code when submitted

## Writing

* A [completed reflection](writing/reflection.md) which:
  * Is at least `200` words
  * Features _no_ `TODO`s