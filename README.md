# funnel_analysis
This document illustrates our funnel analysis of Metrocar Company's data.
### Team Members
- **Jelena Biletic** - Data Analyst
- **Timon Stolzenber** - Data Analyst
- **Mohamed Shehata** - Data Analyst
- **Abdullah Nouh** - Data Analyst
### Tools
- **SQL**: We used SQL to efficiently extract, filter, and aggregate data from the database for precise analysis.
- **Python**: Python was employed for in-depth analysis and visualization, leveraging its powerful libraries to present insights clearly and effectively.
# **Metrocar: Funnel Analysis**
### **Executive Summary**
## **INTRODUCTION**
The goal of this analysis is to evaluate key aspects of user behavior and platform performance for a ride-hailing service, with a specific focus on conversion rates throughout the user journey. Understanding how users interact with the app, from downloading it to completing a ride, is essential for identifying areas where improvements can be made. Additionally, the analysis examines ride availability, user satisfaction, and payment success to provide actionable insights into service quality and business sustainability. By identifying bottlenecks in the user experience and operational inefficiencies, this analysis aims to recommend strategies for enhancing both customer satisfaction and platform performance.

## **METHODOLOGY**
To conduct this analysis, data was extracted using **SQL** to filter and aggregate relevant metrics from the platform’s database. SQL queries were used to examine user funnel stages, including app downloads, sign-ups, ride requests, ride completions, and payments. These stages were analyzed to determine conversion rates and identify points of drop-off throughout the user journey.

In addition to **SQL**, **Python** was utilized for deeper analysis and data visualization. With libraries such as **Pandas** and **Plotly**, data was further explored to examine trends in ride requests, cancellations, and waiting times. Python also facilitated the creation of interactive visualizations to illustrate key findings, such as conversion rates and user satisfaction metrics. Finally, qualitative analysis was conducted on user feedback, particularly ratings and comments, to uncover patterns in user dissatisfaction and operational shortcomings.

## **KEY FINDINGS**
The initial conversion from app download to signup is quite strong, demonstrating good user engagement from the start. The conversion from signup to ride requested is also notably high, suggesting that users quickly find value in the platform once they sign up. However, **the conversion rate from ride requested to ride completed (50.2%)** shows that half of the users who request a ride do not complete it.

<img width="1065" alt="Screenshot 2024-09-16 at 14 49 18" src="https://github.com/user-attachments/assets/493c53e5-5fd9-4335-b223-b9ac49295a06">

This points to potential issues with ride availability, user interface challenges, or external factors affecting ride completion. While **90% of accepted rides are successfully completed, the acceptance rate of 64.4%** suggests that there might be opportunities to improve how rides are matched between drivers and riders.

<img width="1065" alt="Screenshot 2024-09-16 at 14 50 00" src="https://github.com/user-attachments/assets/259ff401-465b-4b31-94e6-47c8165101ea">

<img width="1056" alt="Screenshot 2024-09-16 at 14 51 39" src="https://github.com/user-attachments/assets/1f4e71a2-5fb1-45de-89b1-bd3522ef82f6">

**Rush hour, particularly between 8-9 AM and 4-7 PM**, experiences the highest volume of ride requests, as well as the most cancellations. A significant number of rides are canceled without being accepted, which implies that there are challenges in matching drivers to requests during these peak periods. Furthermore, even for rides that are accepted, cancellations occur frequently during rush hours, likely due to long waiting times, which frustrate both users and drivers. These issues are compounded by long wait times during peak periods, potentially leading to user dissatisfaction and reduced future engagement with the platform.

<img width="648" alt="Screenshot 2024-09-16 at 15 42 08" src="https://github.com/user-attachments/assets/fbd6109e-6ac9-4b59-b898-cab7de7e73d6">

Another major area of concern is user dissatisfaction, with **29.7% of users leaving 1-star ratings**. The most frequent complaints involve drivers canceling last minute, unsafe driving, unprofessional behavior, app crashes, and inaccurate arrival times. Additionally, many comments mention poor vehicle conditions and overcharging incidents, further damaging user trust. Finally, while payment success rates are high, **4.9% of transactions fail**, which could be caused by technical problems, user mistakes, or system inefficiencies.

<img width="1060" alt="Screenshot 2024-09-16 at 14 55 06" src="https://github.com/user-attachments/assets/b8a44166-fecb-498e-81f9-4d7af22d982a">

## **RECOMMENDATIONS**

To address the challenges of **Rush Hour Ride Availability and Cancellation Issues**, it is essential to:
* **Increase driver availability**, particularly during peak hours. Expanding the driver pool or offering incentives for drivers to work during rush hours could help reduce waiting times and lower cancellation rates.
*  **Optimizing the ride-matching algorithms** will ensure that available drivers are more efficiently paired with waiting riders.
*  **Improving driver retention** by addressing their concerns and improving satisfaction levels will help reduce cancellations and ensure a smoother user experience.

For **User Dissatisfaction**:
* **Improving driver training and screening processes** will help mitigate complaints about unprofessionalism and unsafe driving.
* **Enhancing app reliability** by fixing bugs, reducing crashes, and improving accuracy in ride arrival times is critical to ensuring a seamless experience.
* **Vehicle maintenance and cleanliness** should also be prioritized, as poor vehicle conditions have been a frequent source of complaints.
* **Strengthening customer support** to handle issues like overcharging and poor service resolution will build trust and help retain users.

To address **Unsuccessful Payments**: 
* **A thorough analysis of the failed transactions** is needed to identify specific causes, whether technical, user-related, or system-based.
* **Implementing system upgrades** to resolve these issues and prevent future payment failures will contribute to a smoother, more reliable payment process for users and help maintain business sustainability.

## **PROJECT SUMMARY**

Watch video presentation of this project [MetrocarVideo](https://drive.google.com/file/d/1pOhBbxPcfLkeg2pGkCgK9M5BNU_svpVx/view?usp=sharing).

See the presentation of this project [MetrocarPresentation](https://docs.google.com/presentation/d/1x1k4PuT338_0PH4YwOaLVOYl1w-rU7tY0RuKssNb3so/edit?usp=sharing).
