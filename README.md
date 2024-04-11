**Background** 

This study applies advanced machine learning techniques to analyze participant check-ins for the Carrera 5K Race and explore opportunities for expanding the GirlsMPowered program. 

The two key initiatives handled in this project for the United Neighborhood Organization are: 
1) Predicting participant turnout for the upcoming Carrera Day of the Dead 5K Run, an annual Día de los Muertos celebration that also funds other UNO programs.
2) Expanding the GirlsMPowered Program, a mentorship initiative supporting girls, across more schools.

Overall, these methods contribute to understanding participant demographics and enable accurate predictions of event attendance and informing decisions on program expansion initiatives.


**Methods**

For Carrera Day of the Dead 5K Run:

Utilizing data from 2015 to 2023, including program and race participant datasets alongside Census data, logistic regression, decision trees, and random forests were employed to predict race participant check-ins. Hyperparameter tuning techniques were utilized to prevent overfitting. 

Additionally, the influence of demographic factors on participant attendance was examined using Kaplan-Meier and Cox Proportional Hazard analyses, revealing significant one-year participation trends. 

For GirlsMPowered program:

Employing K-means to identify zip codes that belong to clusters similar to the focus area for program expansion.

**Results**

For  Carrera Day of the Dead 5K Run:

60% of the runners are likely to only join for the first year, and the further away the registration date from the actual event, the lower the probability of the participant showing up​. 

For the GirlsMPowered program:

After conducting the Silhouette Score and Elbow method, the optimal number of cluster K is 5, and similar zip codes within the Chicago area are shown in the poster with a map visualization. 
