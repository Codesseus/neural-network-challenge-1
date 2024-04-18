# neural-network-challenge-1

This program creates a deep neural network and runs predictions on it to determine the binary classification of a person's credit ranking (0 for bad, 1 for good)

We were asked to answer the folllowing questions as part of the assignment. I have included these answers both in the assignment as well as below.

---
**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

We would need to collect data about both their history as a student (major, gpa, etc.) as well as financial data about them (payment history, amount of financial aid already taken, etc.). This data is necessary since awarding financial aid to a student is based on the return on investment of that student, in this case how likely are they to make good use of the financial aid and how likely are they to successfully pay it back.

---
**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

I believe that the model would be using collaborative filtering because the user we want to create a recomendation for (a student) likely has not finished college. This means we haven't seen how likely we are to see a positive return of investment based on the users own history, but other students like them have finished college so we should be able to compare our user to previous similar users to determine how likely we are to see a good return on our investment.

---
**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**

The first real world challenge I see is that people change overtime, a student fresh out of high school who is overwhelmed by being responsible for their own lives for the first time is not going to be as successful as a junior or senior who has weathered those challenges. Therefore making recomendations based on success of a student will potentially leave out promising candidates who might not have much figured out now but will change in a year or two's time and be more than capable of making full use of the loan. My reccomendation to account for that would to be a little more forgiving when handing out loans to people earlier in their college career. 

The second real world challenge I see would be bias against protected groups that could creep in due to how data is collected. If data is used on the location of the college it is possible that people attending colleges in historically less economically successful locations would be have their scores lowered only because they wanted to attend that particular college, and no fault of their own. This is just one example, but I am sure there are others as to how bias could creep into the data if it is not cloesly monitored.