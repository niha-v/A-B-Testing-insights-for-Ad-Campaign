# A/B Testing  Insights for AdCampaign

## 📊 **Project Overview**

In this project, we analyze user behavior data from an A/B test where:
- **Experimental Group**: Exposed to an Ad Campaign.
- **Control Group**: Shown a PSA or no ad at all.

We use **statistical methods** such as **Bootstrapping**, **Independent Samples T-Test**, and **Chi-Square Test for Independence** to evaluate the impact of the Ad Campaign on user conversions.

---

## 🎯 **Key Questions**
1. **Campaign Success**: Did the Ad Campaign lead to a significant increase in conversions?
2. **Attributable Impact**: How much of the success can be directly linked to the ads?
3. **Statistical Significance**: Are the results statistically significant?

---

## 📂 **Dataset**
The dataset contains the following columns:
- `user_id`: Unique identifier for each user.
- `test group`: Whether the user was in the "ad" (Ad Campaign) or "psa" (PSA) group.
- `converted`: Whether the user converted (1) or not (0).
- `total ads`: Number of ads seen by the user.
- `most ads day`: Day of the week the user saw the most ads.
- `most ads hour`: Hour of the day the user saw the most ads.

---

## 🛠️ **Methods Used**
1. **Bootstrapping**:
   - Estimated the **95% confidence interval** for the difference in conversion rates between the Ad and PSA groups.
2. **Independent Samples T-Test**:
   - Tested whether the **average conversion rates** differed significantly between the two groups.
3. **Chi-Square Test for Independence**:
   - Tested whether there was a significant association between the `test group` and `converted` outcome.

---

## 📈 **Results**
1. **Bootstrapping**:
   - **95% Confidence Interval for Difference in Conversion Rates**: (0.0059, 0.0093)
   - Interpretation: The Ad Campaign led to a **0.59% to 0.93% increase in conversions** compared to the PSA group.
2. **Independent Samples T-Test**:
   - **T-statistic**: 0.2139
   - **P-value**: 0.8306
   - Interpretation: No significant difference in **average conversion rates** between the groups.
3. **Chi-Square Test for Independence**:
   - **Chi-Square Statistic**: 54.0058
   - **P-value**: 0.0000
   - Interpretation: A significant association exists between the `test group` and `converted` outcome.
     
---

## 📊 **Visualizations**
Here are some key visualizations from the analysis:
Conversion Rates by Test Group
![Image 1](Image 1/image.png)








📧 Contact
For questions or feedback, feel free to reach out: niharika.umrani@gmail.com
---



Let me know if you’d like to customize this further! 😊


