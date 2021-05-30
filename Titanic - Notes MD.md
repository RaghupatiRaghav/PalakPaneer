# Titanic - Notes


**Git Workflow:**
Git pull <remote url>
Git add . 
Git commit -m "commit message"
Git push origin master - If error, run git pull again and then run git push 


## Understanding Data:
- SibSp: spouses or sibling
- Parch: bacho ke liye parch is no of parents on board, parents ke liye parch is no of bache on board
- Many people are travelling on the same ticket, in most cases, these people will be related.

## EDA Data: - Matplotlib, Seaborn
- Manak bar graph of place of boarding for each pclass
- Manvi survival vs gender and age 
- Raghav avg age of males and females
- Raghav avg age of males and females in diff pclass
- Raghav difference in survival rates in males and females of diff pclass
- Manak pclass ka survival
- Manvi avg fare of pclass
- Manvi cabin and survival within each pclass
- Manak parch and survival 
- Manak sibsp and survival
- Manak parch and sibsp within each pclass
- Raghav sibsp+parch = total family, survival and total family correlation 
- ticket number - does pool of people survive with family?
- Raghav sex, age and pclass ko combine karke make a bar graph

## Cleaning and Processing Data: - Pandas
- Manvi fill rate
- Manvi separate name column into first name, title and the rest of the name 
- Manak Numerical flags for gender and embarked variables
- missing values - before applying the algo 
- manak remove the col with low fill rate, remove missing values
- raghav pipeline random forest
- manvi pipeline random forest - confusion matrix
- age fill rate and fare fill rate
 - tracker for d/f models

## Suggestions: 
- prepare train and test dfs - all - done
- take the input and run rf and generate submission files - Raghav - done
- remove passenger id - Manak
- can remove fare - Manak
- pclass without dummies - Manak
- gender without dummies - Manak
- feature engin - gender*pclass - Raghav -done
- g = 1, pclass = 1, new_var = 1
- baseline accuracy - Manvi
- make a markdown file for notes - Manvi - done
- impute missing values in train - Raghav - done
- modify number of trees 









