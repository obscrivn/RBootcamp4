---
title       : Preparation
description : Upload files from here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:b44077c753
## Files Needed for this workshop

* Slides: [https://www.slideshare.net/obscrivn/rbootcamp-day-4](https://www.slideshare.net/obscrivn/rbootcamp-day-4)
* R Code [http://cl.indiana.edu/~obscrivn/docs/DavisBoot4.R](http://cl.indiana.edu/~obscrivn/docs/DavisBoot4.R)
* Text File 1 [http://cl.indiana.edu/~obscrivn/docs/cities.txt](http://cl.indiana.edu/~obscrivn/docs/cities.txt)
* Text File 2 [http://cl.indiana.edu/~obscrivn/docs/troops.txt](http://cl.indiana.edu/~obscrivn/docs/troops.txt)
* Text File 3 [http://cl.indiana.edu/~obscrivn/docs/temps.txt](http://cl.indiana.edu/~obscrivn/docs/temps.txt)

When you are done downloading files and you have studied the lecture, select DONE and proceed to the next exercice.

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
msg2 <- "Great. Make sure to study slides"
test_mc(correct = 1, feedback_msgs = c(msg1,msg2))
```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:4b41706675
## Practice code

- In this exercice you will be working with your own RStudio and take as much time as you need. 
- We have a set of tasks, build these plots in your own R script. When you are done, click DONE and proceed to the next section which provides the answers.

**Plot 1**
- Let's look at the Fischer iris dataset. It gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. It's available in base R.

**Plot 2**
- ` qplot() ` will assume the first two parameters are aesthetic mappings for x and y. We can, however, set more parameters for more aesthetic mappings.
 
- Use qplot to plot sepal length vs sepal width and add a mapping of species type to shape. 

**Plot 3**
- Now use qplot to plot sepal length vs sepal width and add a mapping of species type to color instead of shape.


** Plot 4**
- Now use qplot to plot sepal length vs sepal width and mapping of species type to both color and shape. Assign this ggplot opbject to a variable called ` iris.plot `.
 
**Plot 5**
- Read the help file for ` scale_color_manual() `
Now add a color scale to ` iris.plot ` so that the species are mapped to purple, brown, and steel blue. Don't worry about which species goes to which color unless you want to.

**Plot4**
- Let's say you want the guide off to the right to only use color not shape. Read the help file for ` scale_shape() `
 
` ?scale_shape() `
 
- Use this to remove the shape information from the guide. Call this final ggplot object ` iris.plot3 `

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

```
