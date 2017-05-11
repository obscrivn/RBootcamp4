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

--- type:NormalExercise lang:r xp:100 skills:1 key:f80ee7a73e
## Practice code

In this exercice you will be working with your own RStudio and will just copy and paste answers here

Let's look at the Fischer iris dataset. It gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. It's available in base R.
 
Use qplot to plot sepal length vs sepal width in the iris dataset.


*** =instructions
- Use qplot to plot sepal length vs sepal width in the iris dataset.


*** =hint


*** =pre_exercise_code
```{r}
# You can also prepare your dataset in a specific way in the pre exercise code
#load(url("https://s3.amazonaws.com/assets.datacamp.com/course/teach/movies.RData"))
#movie_selection <- Movies[Movies$Genre %in% c("action", "animated", "comedy"), c("Genre", "Rating", "Run")]

# Clean up the environment
#rm(Movies)
```

*** =sample_code
```{r}
# Use qplot to plot sepal length vs sepal width in the iris dataset.
#qplot() will assume the first two parameters are aesthetic mappings for x and y.

```

*** =solution
```{r}
#Use qplot to plot sepal length vs sepal width in the iris dataset.

#qplot() will assume the first two parameters are aesthetic mappings for x and y.
qplot(Sepal.Length, Sepal.Width, data=iris)


```

*** =sct
```{r}

test_output_contains("qplot(Sepal.Length, Sepal.Width, data=iris)")

success_msg("Good work!")
```
