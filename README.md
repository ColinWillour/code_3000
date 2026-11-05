# code_3000
Collection of Assignments for CSE 3000: Contemporary Issues in Computer Science and Engineering

_Note_: Odd-numbered assignments are in HuskyCT, while even-numbered assignments are found in this repo and can be submitted to Gradescope via a Github connection.

## Outline of Assignments

### Module 02: Bot Predictor
Your goal is to build a machine learning model using given data and a Python template. You'll make changes to the GradientBoostingClassifer in mod02_build_bot_predictor.py and then test your changes in mod02_test_bot_predictor.ipynb. Can you minimize the misclassification rate on the test set?

### Module 04: Model Bias
You are given a model that was built to predict a mystery variable using zip code, income, and education level. The variable "group" represents a demographic that is prohibited and was NOT used in the model. Your goal is to use the SHAP package to review this model for bias.

### Module 06: Data De-Anonymization
Your goal is to connect anonymized data back to its source data and check the match rate. To complete this activity, write functions in the "deanonymize" script to (1) link the records in the two datasets and (2) calculate the rate at which you are successful doing so. 

### Module 08: Sustainability in Computing
You will be given a toy dataset and have the opportunity to explore the potential effects of choosing sustainable energy sources to perform computations. You'll code the energy calculation in "sustainability calculations" script, and then you can review the results of various decisions in the "check calculations" notebook. 

## Personal Ethics Statement

Chapter 5 of *Ethical Machines* argues that most ethics statements fail because they list nice-sounding values ("we value fairness, transparency, and privacy") without saying what those values require anyone to actually do. I agree, and I want my own statement to avoid that trap by tying each value to a concrete commitment.

- **Because I value fairness, I will** test the models and systems I build for disparate impact across groups, including groups that were never used as inputs, since proxies like zip code can quietly reintroduce bias.
- **Because I value privacy, I will** treat "anonymized" data with skepticism, collect only what a project needs, and never re-identify people without their consent and a legitimate purpose.
- **Because I value honesty, I will** be able to explain what my systems do and where they fall short, and I will not overstate a model's accuracy to make it easier to ship.
- **Because I value responsibility, I will** consider the people affected by my work, not just the people paying for it, and I will speak up or walk away when a project crosses a line I can name in advance.

For me, ethics is less about having the right opinions and more about deciding ahead of time what I will and will not do, so that when pressure comes from a deadline or a manager, the decision has already been made.
