---
title       : Answers
description : Check the answers to your previous ggplot activities


--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:8b0b02237d

## Answers
When you are done reviewing your answers, click DONE.

Proceed to the new assignment in your course **Introduction** which will provide more details about ggplot. Enjoy the course!

**Plot 1**

` qplot(Sepal.Length, Sepal.Width, data=iris) `

**Plot 2**

` qplot(Sepal.Length, Sepal.Width, data=iris, shape=Species) `

**Plot 3**

` qplot(Sepal.Length, Sepal.Width, data=iris, shape=color) `


**Plot 4**

` iris.plot <- qplot(Sepal.Length, Sepal.Width, data=iris, shape=Species, color=Species) `
 
**Plot 5**

` iris.plot2 <- iris.plot + scale_color_manual(values = c("purple","brown","steel blue")) `

**Plot6**

` iris.plot3 <- iris.plot2 + scale_shape(guide = 'none') `

*** =instructions
- DONE
- Not done yet

*** =hint


*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg1 <- "Click Done"
msg2 <- "Great. Go ahead and chec your anwers"
test_mc(correct = 1, feedback_msgs = c(msg1,msg2))
```
