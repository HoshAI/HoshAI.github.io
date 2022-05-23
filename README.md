# My_portfolio_website
Ayodeji's data science portfolio

[PRROJECT 1: Data Science Salary Estimator](https://github.com/hoshAI/ds_salary_proj)
* Created a tool that estimates data science salaries (MAE ~ $ 11k) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job description from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
* Optimised Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
* Built a client facing API using flask

![](/images/position_by_state.png)


# [Project 2: Ball Image Classifier](https://github.com/hoshAI/ball_image_classifier)
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sport from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rulesof the game. This is the underlying model for building something with those capabilities.

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the needof an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34.This create time efficiencies and solid results.

![](/images/matrix_results.png)
