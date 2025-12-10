# Assignment 6 Part 1 - Writeup

**Name:** _______________  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**
The R^2 score tells me the strength of the correlation in my model. If R^2 is close to 1 that means that the correlation is almost perfect and if it is close to 0 that means there is barely any correlation present.



---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**
The MSE is the average of how far off my predictions are. A bigger MSE means worse predictions. We square the errors instea dof just taking the average of errors because if there is a positive and negative mistake there is a chance they would cancel out which would make it seem as though my average is perfect. 



---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**
I would not trust this model to predict a score for a student who studied 10 hours because that is the hour where the correlation started to weaken. 



---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**
The relationship between hours studied and test scores is strong, linear, and has a positive correlation. This means the more they studied, the higher they scored(in most cases).



---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Curve
2. Extra credit question
3. Study Methods


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**
So that our program can read the data accurately instead of just outright, but not knowing what it is doing. #practicemakesperfect



---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**
The most challenging part of this assignment was trying to catch up after being absent for like a week, and also getting all the functions down. While tracing the code from the ice cream example I forgot to include this one line of code which made my scatter plot come across as empty. I just need to get into the groove of checking my code more, but I asked Mr.Berg for help tracing.



---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**
A real world problem I could solve with linear regression is F1 crashes. My X value would be tire size, and my Y value would be amount of crashes. This relationship might be linear because the size of the tire effects how much grip it has on the ground, how many laps it can go without a change, and how much support it has for the car.



---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
