# Capstone
My capstone project

Classification of Spam emails using Machine Learning

Problem statement
Classifying spam emails is an interesting topic because it could help sort emails more acurately and could show which machine learing algorithm is the best for projects like this. Often times, spam emails are not sent into the spam inbox and ocasionaly regular email are sent to the spam inbox. My programm would hopefully help solve this problem for people.

Data
The data set I used was on kaggle as a cvs file. It had over five-thousand message labeled as as spam or not spam and most of the projects on kaggle that I looked at used that data set with acurate results, so I followed suite and imported that data set into Jupiter Notebook. The only problem was unbalanced data, which might have affected my results

Approach
For my aproach, I wanted test three different machine learning algorithms: MultinomialNB, Logistic Regression, and Random Forest. I originaly tried Multinomial NB, but it always predicted a regular message, which might be caused by the unbalanced data set, so then I tried random forest with much better results. When I tested random forest's acuracy I got around 97% acuracy, 90% recall, and 98% precision, which is really high.

Supervised learning models are models that are trained by labeled data to predict future outcomes, which is what I trained to predict whether a message is 'ham' or spam.

Deliverables
Code: data visualization, exploratory data analysis, machine learning algorithms, predicted and classified emails between spam and 'ham'.
