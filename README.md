
# Machine Learning 
## Creator
Roberto Gonzalez - roberto.gonzalez.vallejo@gmail.com [![GitHub](social_icons/gthb.png)](https://github.com/roberto-g-v/)  [![Linkedin](social_icons/lkdin.png)](https://www.linkedin.com/in/roberto-gonzalez-vallejo-6ba894144/) [![Twiter](social_icons/twtr.png)](https://twitter.com/RobertoGlezV)  

---
Table of contents <a name="toc"></a>

1. [Jupyter Notebook File](#jnb)
2. [Models](#mdl)
2. [Answers](#ans)

---

### Notebook for Suport Vector Machine and Random Forest <a name="jnb"></a>
<sub><sup>[Go back to the table of contents](#toc)</sub></sup>
<br>

[![Jupyter Notebook SVM](social_icons/clickherejn.png)]https://github.com/roberto-g-v/machine-learning-challenge/blob/main/starter_code/rgv_SVM_model.ipynb)
[![Jupyter Notebook RM](social_icons/clickherejn.png)]https://github.com/roberto-g-v/machine-learning-challenge/blob/main/starter_code/rgv_RM_model.ipynb)

---

---
### Models <a name="mdl"></a>
<sub><sup>[Go back to the table of contents](#toc)</sub></sup>
<br>
Suport Vector Machine Results:
Training Data Score: 0.8455082967766546
Testing Data Score: 0.8415331807780321


Random Forest Results:
Training Data Score: 1.0
Testing Data Score: 0.83492321

---
### Answers <a name="ans"></a>

1. What does the results for Suport Vector Machine mean?
Results Scores for Train and test had and accuracy of 0.84 which means 84/100 were precise inside the grid. Moreover with the use GridSearchCV the results were even more tuned to the model's parameters having accuracy of 0.8823155822702828 best score. ?
<br>

1. What does the results for Random Forest mean?
The default for model result was 1.0 and the default of max_depth is None. This combination allows your DecisionTreeClassifier to grow until there is a single data point at each leaf. Since I am having 100% accuracy, I would assume a duplicates in your train and test splits or it had to do with overfit my training data.

# machine-learning-challenge copyrights 2021
<br>
