**FINDINGS**

The project was initiated by collecting the necessary documents and data from both branches. Total sales quantities and revenues between October 2024 and April 2025 were obtained from each branch. In addition, monthly revenue data and the price ranges of each branch were also provided separately.

Once the data collection was completed, data cleaning and preprocessing were carried out, as detailly shown in the 'data processing' file.

Following the preprocessing phase, data analysis and visualization were performed.

Here are the throughout analysis of the obtained figures:

**Top 15 Products by Revenue - Hilltown vs. Balçova**

*Hilltown Branch:*

At the Hilltown branch, the Ohannes Cheese Burger and Regular Cheese Burger emerge as the clear revenue leaders, significantly surpassing other items. Other popular items include various burger types (Tandır, Mushroom, Classic, Smash) along with beverages like Coca-Cola and beer. Considering tandır, bifteks and smash burger are items that contain more meat, along with the general domination of meat based burgers and beers, assumption that customer base is leaned more towards premium menu items and are not underage can be made.

![ht top 15](https://github.com/user-attachments/assets/dbae5d8b-9aef-46ec-a5f6-ec57bea0899d)


*Balçova Branch:*

Balçova’s revenue leaders differ notably; Bilader Menü is the top product, followed closely by Smash and Cheese burgers. The presence of menus (Bilader, Ulti) among the top products shows an inclination toward bundled offerings, and the existence of chicken burger types in the top 15, reflects a different consumer preference and possibly a younger, student-oriented customer base. This analysation can be confirmed by the location of Izmir Economics University, which is really close to the Balçova branch.

![balçova top 15](https://github.com/user-attachments/assets/ea0f06d5-5981-43c8-86f7-2cf5bb962520)


*Comparative Analysis:*
Hilltown emphasizes premium individual items, while Balçova prefers bundles and diverse offerings. This suggests distinct customer profiles at each location, with Hilltown appealing to individual customers with disposable income and Balçova targeting student groups.

**Average Daily Revenue by Month (October 2024 - April 2025)**

*Hilltown Branch:*

Hilltown branch follows an unstable graph, there are many effects that may be the cause of these fluctuations, some of which we are examining in this particular research. The extreme increase in April may be due to better weather, while the drop in February may be due to various reasons, along with the month being shorter, bad weather and winter breaks. 

![ht daily](https://github.com/user-attachments/assets/162c4f08-a349-4d4d-a409-717c586760bf)


*Balçova Branch:*

Balçova reveals a consistent upward growth trend across all months, without significant fluctuations. This consistent increase highlights the branch’s progressive market penetration and stable customer acquisition, especially around the university vicinity.

![balçova daily](https://github.com/user-attachments/assets/b6d86d81-3054-49d9-a577-0e87261b4250)


*Comparative Analysis:*

Hilltown experiences volatile revenue likely due to seasonality tied to mall traffic, while Balçova shows steady growth indicative of a stable and gradually expanding customer base around the university. Considering that Balçova branch has opened in October 2024, the gradual increase in general indicates a positive sign. Comparing both branches, Hilltown consistently maintains higher daily revenues. However, Balçova’s steady and continuous growth pattern, especially evident from January to April, suggests strong market adaptation and growing popularity among local customers, potentially younger demographics.

![ht vs balçova daily](https://github.com/user-attachments/assets/7a8cf40d-e7ff-4104-9887-95f836153b86)

**Average Temperature and Rainy Days in İzmir (Oct 2024 - Apr 2025)**

To examine the relationship between average daily values and weather conditions, data of the weather at Izmir was gathered from AccuWeather. Analyzing the weather data, Izmir experiences its lowest temperatures and most rainy days in December-January. Weather patterns align inversely; colder months coincide with more rainy days. Understanding these patterns is crucial for assessing their impact on consumer behavior at both locations.

![izmir hava](https://github.com/user-attachments/assets/1b01b200-c55d-4868-b8ec-f9a22afeea83)

**Monthly Additional School Vacation Days (High Schools)**

December and January witness the highest additional vacation days, significantly affecting the Hilltown branch, considering its mall location which may attract more family visits. Balçova, closer to a university, is less affected by high school vacations.

![izmir tatil](https://github.com/user-attachments/assets/0e58cd49-3b69-4c3c-8c83-f0bbf391fcaa)

**Correlation Analyses:School Vacation Days vs. Daily Revenue**

*Hilltown Branch:*

Moderate positive correlation (r=0.35) suggests school vacations moderately boost Hilltown’s sales, likely due to increased mall traffic from families and high school students.

![ht tatil](https://github.com/user-attachments/assets/129a52f9-f8f2-4e21-83a3-49fdc8236da9)


*Balçova Branch:*

Negligible correlation (r=0.10) indicates that high school vacations do not significantly affect sales. This aligns with expectations, as university-related customer demographics are typically less impacted by high school vacation periods.

![balçova tatil](https://github.com/user-attachments/assets/eee7a099-21fb-4d33-9a3d-953cc8681300)

**Daily Revenue Trends with University and High School Winter Breaks**

*Hilltown Branch:*

The Hilltown branch revenue trend reveals noticeable volatility, particularly during the high school winter break. The initial revenue dip in February corresponds closely with the school vacation period, followed by a substantial increase afterward, suggesting temporary disruption followed by a quick recovery once regular schedules resume. Though the correlation analysis above demonstrated a moderate positive correlation between high school vacations and daily revenue of Hilltown, the now found result shows, long periods of vacation might result with possible customer base going out of town, hence having a drop in daily revenue.

![ht sömestr](https://github.com/user-attachments/assets/e1e28e11-44a2-4340-8631-01d2a71bae96)


*Balçova Branch:*

The gradual increase of the branch slows down mid January, continuing until February. Izmir Economy University (IUE) had winter break during 12 January 2025-10 February 2025. This setback encourages the findings above of IUE students being the majority of the customer base as IUE has very limited dormitory and most students go home in winter breaks. 

![balçova iue](https://github.com/user-attachments/assets/f1718d70-3e8f-466a-b55f-349bebc4686b)

*Comparative Analysis:*

The comparison clearly shows Hilltown's susceptibility to school vacation disruptions contrasted with Balçova's stability, underlining differing customer demographics and dependency on school schedules.

**Hypothesis Test Results**

*Price Difference vs. Sales Quantity Difference:*

Null Hypothesis (H₀): There is no significant relationship between the price difference and sales quantity between the two branches.

Alternative Hypothesis (H₁): There is a significant relationship between the price difference and sales quantity between the two branches

The correlation analysis yielded no significant relationship (r=-0.10, p-value=0.277) between price differences and sales quantities across branches. We failed to reject H₀, this implies customers’ purchasing decisions are not heavily influenced by price variations alone, suggesting other factors such as location convenience, menu preferences, and consumer habits play a more critical role in determining sales performance.

![h0 sales](https://github.com/user-attachments/assets/8148fc6c-5bcc-46c6-8706-c94d117b8f3a)


*Weather Impact on Sales:*

Null Hypothesis (H₀): Rainy weather effects on sales do not differ significantly between branches.

Alternative Hypothesis (H₁): Rainy weather effects on sales differ significantly between branches.

No significant difference was observed (Fisher Z=-0.76, p-value > 0.05) in the effect of rainy weather on sales between branches. We fail to reject H₀, weather variations similarly affect both branches without significantly favoring one over the other.

<img width="1136" alt="Screenshot 2025-04-25 at 16 57 17" src="https://github.com/user-attachments/assets/16930f99-89cc-4b6b-b3e5-1de43106f51e" />


*Location Type Impact on Sales Advantage:*

Null Hypothesis (H₀): There is no significant relationship between the location type and the sales advantage.

Alternative Hypothesis (H₁): There is a significant relationship between the location type (mall vs. university area) and the sales advantage.

A highly significant relationship (Chi-Square=127.94, p-value<0.001) was found between location type (mall vs. university area) and sales performance advantage. We rejected  H₀, mall locations notably outperform university areas in absolute revenue terms, emphasizing the strategic advantage of being situated in high-footfall mall environments.

<img width="1071" alt="Screenshot 2025-04-25 at 16 58 19" src="https://github.com/user-attachments/assets/ccdf0936-bd98-4d46-a786-5a9312d84ca0" />

**Extra Findings**

*Correlation Analyses: Temperature vs. Daily Revenue*:

Hilltown Branch: Displays a weak positive correlation (r=0.30) with average temperature, indicating slightly increased revenues in warmer weather, possibly reflecting higher mall foot traffic during pleasant weather conditions.

![ht hava](https://github.com/user-attachments/assets/31b35baa-f360-444e-b2e4-6ce4861a6998)


Balçova Branch: In contrast, reveals a weak negative correlation (r=-0.25), suggesting minor decreases in revenue with increasing temperature. The slight decline could reflect reduced local customer visits during warmer months, potentially due to university schedules or decreased local activities.

![balçova hava](https://github.com/user-attachments/assets/5b9833b2-e9e9-4a70-a02f-e856d835b4ec)

To complement the findings, average monthly temperature trends indicate that colder months (December-January) correspond to lower temperatures and higher rainfall. Hilltown's positive correlation with rising temperatures suggests increased consumer willingness to visit the mall during milder weather conditions. Conversely, Balçova's negative correlation hints that university-area customers reduce local spending during warmer months, potentially shifting their leisure activities elsewhere. Understanding these subtleties helps better predict customer behaviors and tailor marketing strategies seasonally.

**Recommendations based on Findings:**

Hilltown could leverage promotions and campaigns during school vacations to counteract temporary dips.

Balçova may benefit from maintaining steady, long-term promotional strategies, especially targeting local residents and university staff during academic breaks. Along with increasing number of "menu"s to become more desirable to students. Also campaigns such as discounts on drinks can be applied considering the major differences between sold drink quantities of Hiltown and Balçova branch.

Pricing strategies should focus more on enhancing product appeal and bundle offerings rather than aggressive price competitions, as pricing alone showed minimal impact.

Seasonal marketing and special campaigns aligned with weather trends may optimize customer engagement at both locations, utilizing weather-related insights to predict shifts in customer flow and preferences effectively.

**Application of Machine Learning Models**

After the initial findings and evaluation of hypotheses, Machine Learning models were applied to estimate the monthly revenue of May 2025 for both the Hilltown and Balçova branches.
Two different models were developed and compared: XGBoost and Random Forest. These models were selected due to the small dataset size (7 months), non-linear relationships (multiple interacting factors influencing revenue), and to ensure robustness against outliers and noise.
Same features were used for both models: Average of previous monthly revenues, number of rainy days, number of vacation days excluding weekends (normally, high school vacation days are used for Hilltown and University for Balçova, however, in May they were both the same in İzmir), total sales count of the branch (from October to May), and average prices.

Below are the results and interpretations:

***XGBoost Model***

*Hiltown Branch:*

Monthly revenue for Hilltown Branch in May 2025 was predicted as: ₺3,228,047.00.

<img width="869" alt="Screenshot 2025-05-27 at 22 58 12" src="https://github.com/user-attachments/assets/13d9338c-d532-4efc-b143-1cc3ebd8dd10" />

After this calculation, to validate the model’s reliability, we performed Leave-One-Out Cross Validation (LOOCV).

In order to figure out the predictive power of the Machine Learning model built for estimating the monthly revenue at the Hilltown Branch in May 2025, two key metrics were used:  Mean Absolute Error (MAE) and R-squared (R²) score.

The R² score, also known as the coefficient of determination, was calculated as 0.673. This value indicates that approximately 67.3% of the variance in the monthly revenue can be explained by the features used in the model.

Additionally, the Relative MAE was calculated as 5.33%, which means that the model's predictions deviated from the actual monthly revenue by an average of only 5.33%. This low percentage confirms that the prediction error is small in proportion to the revenue scale.

The LOOCV MAE was approximately ₺172,582.27, which further confirms the model’s ability to make consistent predictions with acceptable deviation from actual revenue values.

In practical terms, this means the model has a moderate-to-strong explanatory power. While it does not capture all of the variability in revenue (due to external factors like promotions, possible rivals, customer behavior, etc.), it performs reasonably well given the limited amount of training data (7 months).

Although the R² score is not perfect, model can be considered reliable for forecasting, especially with a limited data such as this one.

*Balçova Branch:*

Monthly revenue for Balçova Branch in May 2025 was predicted as: ₺1,566,236.50.

<img width="869" alt="Screenshot 2025-05-27 at 23 04 35" src="https://github.com/user-attachments/assets/c80dd98c-5b47-4d53-9603-186900b9e428" />

The R² score, also known as the coefficient of determination, was calculated as 0.679. This value indicates that approximately 67.9% of the variance in the monthly revenue can be explained by the features used in the model.

The Relative MAE was calculated as 17.06%, which shows that the model’s predictions deviate on average by 17.06% from actual revenue values. While higher than in Hilltown, this still reflects a level of error that is reasonable for business forecasting, especially considering Balçova is a new branch.

***Random Forest***

*Hilltown Branch:*












