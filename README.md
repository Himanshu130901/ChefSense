# ChefSense
### Data Analytics Assignment

## Objective
Analyze datasets related to user behavior, cooking preferences, and order trends to derive insights and provide actionable business recommendations.

---

## Datasets
The project utilizes the following datasets:

1. **UserDetails.csv**: Contains demographic information about the users.
2. **CookingSessions.csv**: Logs details of users' cooking sessions.
3. **OrderDetails.csv**: Provides data on user orders.

---

## Tasks Performed

1. **Data Cleaning and Integration**:
   - Missing values were addressed using KNN Imputer to ensure accurate data imputation based on underlying relationships.
   - Standardized column names for consistency (e.g., renaming "amount_(usd)" to "amount").
   - Duplicates were identified and removed to maintain data integrity.
   - Merged datasets using User ID and other shared keys to create a unified dataset for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - **Relationship Analysis**:
     - Investigated correlations between cooking session durations, ratings, and the frequency of completed orders.
     - Discovered that users with higher session ratings were more likely to place subsequent orders.
   - **Popular Dishes**:
     - Analyzed order frequencies to identify the most and least popular dishes. Spaghetti and Grilled Chicken emerged as top choices.
   - **Demographic Insights**:
     - Explored the influence of demographic factors such as age, gender, and location on cooking behavior and order patterns.

3. **Data Visualizations**:
   - Created visual representations of key insights:
     - **Age Distribution**: Displayed as a histogram, showing a bell-shaped curve with the highest engagement in the 25-27.5 age group.
     - **Correlation Plots**: Scatter plots revealed a positive relationship between session ratings and order completion rates.
     - **Order Trends**: Bar charts highlighted higher order frequencies on weekdays compared to weekends, with dinner orders dominating in volume and revenue.

4. **Advanced Analysis**:
   - Conducted predictive modeling to forecast order likelihood:
     - **Models Used**: Logistic Regression and Random Forest.
     - Features included session ratings, demographics, cooking behavior, and historical order trends.
     - Achieved perfect classification accuracy with precision, recall, and F1-scores of 1.0, validating the robustness of the models.
   - Insights from these models were used to propose strategies for improving user engagement and operational efficiency.

5. **Key Insights & Recommendations**:
   - Synthesized findings into actionable insights for business improvement.
   - Recommendations were tailored to address observed trends and enhance user experience.

---

## Key Insights

1. **User Engagement**:
   - Younger demographics, particularly in the 25-30 age range, are the most active participants in cooking sessions and subsequent ordering.
   - Session ratings significantly influence order completion rates, with higher-rated sessions correlating with increased order likelihood.

2. **Popular Dishes**:
   - Spaghetti and Grilled Chicken are consistently the most ordered dishes, suggesting strong user preference for these items.
   - In contrast, Oatmeal recorded the lowest order frequency, indicating potential areas for menu optimization or targeted marketing.

3. **Order Trends**:
   - Weekdays experience a higher volume of orders compared to weekends, possibly driven by structured routines during the workweek.
   - Dinner is the most frequent and lucrative meal category, followed by lunch and breakfast, providing clear priorities for menu planning.

4. **Predictive Analysis**:
   - Predictive modeling outcomes highlight the potential for tailoring user experiences through data-driven personalization, enabling focused marketing campaigns and improved customer satisfaction.

---

## Business Recommendations

1. **Real-Time Dish Personalization**:
   - Leverage spatial data and weather conditions to recommend dishes (e.g., warm meals in winter, refreshing options in summer).
   - Utilize user order history and behavior patterns to refine dish recommendations, ensuring relevance and appeal.

2. **AI-Driven Dish Rotation**:
   - Implement an automated system for dynamic menu adjustments based on order trends and user engagement data.
   - Regularly introduce new items and spotlight underperforming dishes with innovative marketing strategies.

3. **Augmented Reality (AR) Integration**:
   - Develop AR features to allow users to virtually explore dishes before ordering, enhancing decision-making.
   - Provide detailed 3D visuals, including calorie content, ingredients, and pairing suggestions, to enrich the user experience.


---

## Tools & Technologies Used

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Others**: Jupyter Notebook, GitHub for version control

---

## Project Structure

```
├── data/
│   ├── UserDetails.csv
│   ├── CookingSessions.csv
│   ├── OrderDetails.csv
├── notebooks/
│   └── upliance_assessment.ipynb
├── README.md
└── visuals/
    ├── correlation_analysis.png
    ├── popular_dishes_plot.png
    └── order_trends_chart.png
```

---

## How to Run the Project

1. Clone the repository:
   ```bash
  [ git clone [[repository_link](https://github.com/Himanshu130901/ChefSense)]
   ```
2. Install required libraries:
   ```bash
   pip install Pandas, NumPy, Matplotlib, Seaborn, Plotly
   ```
3. Open the Collab Notebook:
   ```bash
   [jupyter notebook [notebooks/upliance_assessment.ipynb](https://colab.research.google.com/drive/1-uMDXkdHHgzjInm5mgNOUIE40MNsLb0f#scrollTo=POLBazt7MkvW)]
   ```

---

## Author
Prepared by Himanshu Sahoo.  
Email: himanshu.sahoo@stat.christuniversity.in

