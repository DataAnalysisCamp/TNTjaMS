---
title       : Sissejuhatus R-i
description : Siin saab tutvuda tarkvaraga R ja teha esimesi samme programmeerimises :) Alustame!
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:496d86d802
How it works

In the editor on the right you should type R code to solve the exercises. When you hit the 'Submit Answer' button, every line of code is interpreted and executed by R and you get a message whether or not your code was correct. The output of your R code is shown in the console in the lower right corner.

R makes use of the # sign to add comments, so that you and others can understand what the R code is about. Just like Twitter! Comments are not run as R code, so they will not influence your result. For example, Calculate 3 + 4 in the editor on the right is a comment.

You can also execute R commands straight in the console. This is a good way to experiment with R code, as your submission is not checked for correctness.

*** =instructions

In the editor on the right there is already some sample code. Can you see which lines are actual R code and which are comments?
Add a line of code that calculates the sum of 6 and 12, and hit the 'Submit Answer' button.
*** =hint Just add a line of R code that calculates the sum of 6 and 12, just like the example in the sample code!

*** =pre_exercise_code

# no pec
*** =sample_code

# Calculate 3 + 4
3 + 4

# Calculate 6 + 12
*** =solution

# Calculate 3 + 4
3 + 4

# Calculate 6 + 12
6 + 12
*** =sct

test_output_contains("18", incorrect_msg = "Make sure to add `6 + 12` on a new line. Do not start the line with a `#`, otherwise your R code is not executed!")
success_msg("Awesome! See how the console shows the result of the R code you submitted? Now that you're familiar with the interface, let's get down to R business!")
