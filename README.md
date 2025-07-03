## **Below is the description and a brief implementation algorithm of the training project**

This project involved solving tasks related to analyzing several aspects of a mobile application for a company that develops mobile games.

The work was done in **Python** using **Jupyter Notebook**.

<hr>

### **Task 1**  
**Retention** is one of the most important metrics for the company. **Your task** is to write a function that calculates player retention (by days since player registration). The data is located in the **shared** folder and has the following structure:  

* **shared/problem1-reg_data.csv** – data on registration time  

| reg_ts    | uid |  
|-----------|-----|  
| 906166566 | 2   |  
| 906344325 | 2   |  
| 906686169 | 2   |  
| 906893386 | 2   |  
| 906980227 | 2   |  

* **shared/problem1-auth_data.csv** – data on user login times  

| auth_ts   | uid |  
|-----------|-----|  
| 906166566 | 2   |  
| 924422172 | 3   |  
| 937374732 | 4   |  
| 947425117 | 5   |  

The function should be written in Python. During the solution, you can test the function on either the full dataset or a sample of the data.

### **Task 2**  

There are results from an **A/B test** where two user groups were offered different sets of promotional offers. It is known that ARPU in the test group is 5% higher than in the control group. However, in the control group, 1,928 out of 202,103 players were paying users, while in the test group, 1,805 out of 202,667 were paying.  

Which set of offers should be considered better? What metrics should be analyzed to make the right decision, and how?  

| user_id | revenue | testgroup |  
|---------|---------|-----------|  
| 1       | 0       | b         |  
| 2       | 0       | a         |  
| 3       | 0       | a         |  
| 4       | 0       | b         |  
| 5       | 0       | b         |  

### **Task 3**  

In the game *Plants & Gardens*, limited-time thematic events are held every month. In these events, players can earn unique garden items, characters, extra coins, or bonuses. To receive rewards, players must complete a series of levels within a set time. What metrics can be used to evaluate the results of the latest event?  

Suppose, in another event, we modified the mechanics so that after each failed attempt to complete a level, the player is rolled back several levels. Would the set of evaluation metrics change? If yes, how?  

<hr>

### **Project Implementation:**  
- Conducted preliminary data analysis (EDA) and preprocessing.  
- Wrote a function to calculate player Retention.  
- Calculated and analyzed product metrics (Conversion Rate, ARPPU, ARPU).  
- Tested hypotheses and analyzed A/B test results using statistical tests in Python (Z-test for independence, Bootstrap).  
- Visualized results in Python using **seaborn** and **matplotlib.pyplot**.  
- Selected metrics to evaluate the results of the latest thematic event in *Plants & Gardens* for the mobile game development company.  

<hr>  
