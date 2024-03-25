- A/B Test Name: Pie Chat/Doughnut Chart
- User Story Number: UI/UX Design
- Metric: Engagement
- Hypothesis: Since users can see their total amount in their weekly budget in a doughnut chart, I hypothesize that users would rather have a doughnut chart than a pie chart with their total below the chart.

- A/B Test Name: Plaid API Integration vs Manual Entry
- User Story Number: US4
- Metric:  Adoption (from the HEART framework), specifically focusing on onboarding completion rates and user retention rates after 30 days.

- Hypothesis:
The primary challenge identified is the potential friction during the user onboarding process for an expense tracking app, specifically concerning the method by which users can connect their financial information. This friction could significantly impact user adoption rates, as the ease of onboarding directly affects a user's willingness to complete the setup process and their subsequent engagement with the app.

The hypothesis is that providing users with the option to connect their financial accounts via Plaid API, compared to manually entering their financial information, will lead to higher onboarding completion rates and improved 30-day retention rates. This improvement is expected because the Plaid API connection simplifies the onboarding process by automating the data entry of financial information, which could reduce the effort and potential errors associated with manual data entry. Consequently, this ease of setup is anticipated to enhance the initial user experience, leading to better engagement and retention.


- Experiment:
The experiment will involve creating two variations of the onboarding process:

Variation A (Control): Users manually enter their financial details to set up their expense tracking.
Variation B (Test): Users use the Plaid API to log in and automatically connect their financial accounts.
The audience for this experiment will consist of new users over a period of one month, with 50% randomly assigned to each variation. This allocation ensures a large enough sample size to detect significant differences in the adoption and retention rates between the two groups.

For tracking purposes, Firebase Analytics will be configured to monitor several key metrics:

Onboarding completion rate: The percentage of users who complete the onboarding process.
Time to complete onboarding: The average time taken to complete the onboarding process.
30-day retention rate: The percentage of users who continue to use the app 30 days after installation.
User engagement metrics post-onboarding: Frequency of app usage within the first 30 days.
These metrics will provide insight into how the method of financial account connection influences the initial user experience and long-term engagement with the app.

- Variations:

Variation A (Control) will utilize the standard onboarding flow, with screens guiding users to manually input their financial details, such as account numbers and balances.
Variation B (Test) will introduce an additional onboarding step where users are presented with the option to connect their financial accounts using Plaid. This variation will include a brief explanation of the benefits of using Plaid for data security and convenience, alongside consent forms as required for data sharing.
For both variations, mockups and design work will focus on clarity, ease of navigation, and providing information about data security and privacy. Our team will create user interface mockups that highlight the differences in the onboarding process, focusing on simplicity and minimizing user effort.

This A/B test plan aims to validate the hypothesis that reducing friction during the onboarding process through the use of Plaid API connectivity will positively impact user adoption and retention, providing a clearer path to improving the overall user experience.
