# Mental Health in Tech Industry Analysis
### *author: Celine Ng*
### *April 2024*

# Project Description
brief overview of the project, what it is about, and what it aims to achieve

## Data source
## Code structure
how files relate with each other, refer to important files
## Methods used

# Conclusion/Results

# Recommendations

# Improvements
1. For section 3, preparing the answers for the questions, I could create one 
   only dataset with 12 columns, instead of 12 datasets.
2. Could try to calculate post-hoc for chi-square tests.
3. Normalize number of users to the population of each country, state.
4. Create perform chi-square tests to check significance in difference in 
   section 3.4. 
5. Dive deeper to other questions from the survey.



TODO:
4. compare tech industry and gender on questioins 10-12
how to compare:
I want to understand what the users stance/opinion and how are the 
   companies dealing to mental health issues (officially and actually)
-seems that trust, communication between 2 parties and social awareness are 
lacking
- there is visual correlation between people with families with mental 
  health and number of users seeking therapists. Between less tech 
  companies and more people are seeking for therapists. Between more 
  females and more people seeking for therapists.
also, more companies are providing mental health coverage. Anonymity barely 
  improved (unclear correlation). Users choose not to bring up mental health
  (hasn't changed over years)
- 
-seems that tech industry has worse mental health than other industries
- seems that female are having a better with this mental health situation
4. Proportion-wise, more surveyed individuals are from outside the tech 
industry, and the number of people seeking help has been increasing.This might suggest that those outside of tech are more likely to participate in therapy. Alternatively, it could indicate that everyone is increasingly likely to use therapy.

5. There are more women in tech, and more people are seeking out help. 
Perhaps it's the women?"

calculate correlation between increase of number of non tech users, and 
users seeking help
AND/OR
plot in separate plots, tech and non tech users for questions 10-12 or key 
questions, to understand if there is more trust and communication in non tech industry
calculate the null hypothesis to confirm difference

pd.crosttab / pivot
chi-test
https://pandas.pydata.org/docs/reference/api/pandas.crosstab.html
https://stackoverflow.com/questions/48035381/correlation-among-multiple-categorical-variables


modules for functions:
to_boolean_none 
yes_no_to_boolean
normalized_category
normalized_category_barplot
contingency_table

user_questions = [1, 2, 3, 4, 5, 13, 20, 21, 22]
mental_health_questions = [6, 7]
company_questions = [8, 9]
company_mental_health_questions = [10, 11, 15, 16, 23]
opinion_questions = [12, 14, 17, 18, 19, 24]

