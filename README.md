# TITANIC-EDA

Introduction:

The sinking of the RMS Titanic on its maiden voyage in 1912 remains one of the most infamous maritime disasters in history. The tragic event claimed the lives of many passengers and crew members, highlighting the challenges and vulnerabilities of early 20th-century maritime travel. In this exploratory data analysis (EDA) project, we delve into the Titanic dataset, a valuable repository of information about the passengers aboard the ill-fated ship. Our goal is to uncover patterns, correlations, and insights that shed light on factors influencing survival rates among the passengers.

Initial Hypotheses:

As we embark on this analysis, we begin with some initial hypotheses that guide our exploration. We postulate that passengers had higher chances of survival if they possessed certain characteristics, namely:

1. **High-Class Ticket**: We anticipate that individuals with higher-class tickets, reflecting a socio-economic status, might have had better access to life-saving resources and evacuation procedures.

2. **Gender – Women**: We hypothesize that women, given the historical precedence of "women and children first" during emergencies, may have had a higher likelihood of survival.

3. **Age – Younger Passengers**: It is conceivable that younger passengers, including children, might have received preferential treatment during the evacuation process, potentially influencing survival rates.

Visualizing Null Values:

Before diving into our hypotheses, it is crucial to address missing data. We will visualize null values within the dataset to identify any gaps in our information and strategize accordingly.

Insights:

As we conduct our EDA, several key insights emerge:

1. **Gender Significance**: Analysis reveals that a passenger's gender indeed plays a pivotal role in survival, with women exhibiting a higher chance of survival compared to men.

2. **Class Disparities**: Higher-class passengers demonstrate a greater survival rate than their counterparts in lower classes, suggesting a potential correlation between socio-economic status and survival.

3. **Age and Siblings Correlation**: Age exhibits a high negative correlation with the number of siblings, hinting at potential familial dynamics during the evacuation.

4. **Children's Survival**: A striking finding is that children below 18 years of age have notably higher chances of surviving the disaster.

Count Plot of SibSp:

The count plot of the variable 'SibSp' provides a visual representation of the number of siblings or spouses accompanying passengers. The majority of individuals appear to have traveled without siblings or spouses, indicating potential isolation during the disaster.

Final Hypotheses Confirmation:

Upon comprehensive exploration and analysis, our final hypotheses are validated:

1. **Gender Survival Disparity**: Women indeed have a higher survival rate compared to men.

2. **Class-Based Disparities**: First-class passengers exhibit a superior survival rate compared to second and third-class passengers.

3. **Age-Related Survival Trends**: Younger passengers, particularly children, showcase a higher likelihood of survival.

Conclusion:

In conclusion, our EDA of the Titanic dataset not only reaffirms historical narratives but also uncovers nuanced patterns of survival. By analyzing variables such as gender, class, and age, we gain a deeper understanding of the dynamics that influenced the fate of Titanic passengers. This exploration not only honors the memory of those aboard the Titanic but also enriches our understanding of the human aspect of historical disasters.
