# Aviation Industry Analysis

# Project Overview
This project seeks to explore aviation risks and generate insights for safer aircraft operations.

# Business Understanding
The company is planning to diversify its portfolio by entering the aviation industry through the purchase and operation of airplanes for both commercial and private enterprises. However, aviation carries inherent risks, including accidents and operational failures, that can lead to significant financial losses, regulatory issues, and reputational damage.
To ensure a safe and profitable entry into this new market, the company must evaluate different aircraft types to identify which ones have historically demonstrated the lowest risk profiles. This will allow leadership to make evidence-based decisions on which aircraft to purchase and operate, thereby minimizing risk exposure while maximizing operational efficiency and long-term growth opportunities.

# Problem Statement
The company currently lacks the expertise and data-driven insights needed to assess the safety and risk levels associated with various aircraft. Without a clear understanding of accident patterns, contributing factors, and risk distribution across different aircraft, the company risks making costly investment decisions.

# Dataset
The data used is an aviation dataset sourced from kaggle.

# Experimental Design
1. Defining the Question
2. Data Preparation
    * Reading the Data
    * Checking the Data
3. Data Cleaning
4. Feature Engineering
5. Performing EDA
6. Summary and Conclusion
7. Data Relevance
8. Recommendations

Detailed analysis of these steps can be found by following this link: https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/WinnieNjorogePhase1Project.ipynb

The presentation slides for this analysis can be found by following this link: https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/Winnie%20Njoroge%20Aviation%20Analysis%20Presentation.pdf 

The Tableau Dashboard can be found by following this link https://public.tableau.com/shared/9D9442F2T?:display_count=n&:origin=viz_share_link

# Technologies and Software Used
--Python 3(Pandas,numpy,seaborn,matplotlib)
--Jupyter

# Summary of Analysis
### Aircraft Accidents Over Time
![Alt text](https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/Images/Aircraft%20Accidents%20Over%20Time.png)
Based on line graph, the accidents report in recent years has decrease as compared to previous years. This could be indicative of improvement in safety of aircrafts in the aviation industry.

### Phase of flight during accidents
![Alt text](https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/Images/Phase%20of%20Flight.png)
A significant number of accidents occur during Takeoff and landing phases. This could be indicative of lack of significant pilot training in landing and taking off. We would therefore advise the company to invest in advanced pilot training can greatly reduce risk.

### Top 20 Makes  and Models with the Highest Aircraft Accidents
![Alt text](https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/Images/20%20top%20accident%20Prone%20Makes%20and%20Models.png)

We can see that aircrafts like Cessna and Piper have the highest count of reported accidents which could be attributed to their widespread use as they are popular and large aircraft manufacturers in the aviation industry.
Other well known and large manufacturers of aircrafts with high accident rates are Bell, Boeing and Beech.
However, compared to Cessna and Piper,  Bell, Boeing and Beech have significantly lower accident rate over the same period of time.

### Top 20 Makes  and Models with the Lowest Aircraft Accidents
![Alt text](https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/Images/20%20least%20accidental%20Makes%20and%20Models.png)

All the makes with the least number of recorded accident in the dataset are comprised of a variety of names which mostly appear to be from less known aircraft manufacturers.
Although these makes have the least reported number of accidents, it may not be indicative of their overall safety, it may merely suggest that these are highly specialized aircrafts built by individuals and not many of them are operational, thereby leading to low reported cases of accidents.

### Aircraft Accident by Purpose of Flight
![Alt text](https://github.com/NjorogeWinnie/Aviation_industry_analysis/blob/main/Images/Purpose%20of%20Flight.png)

From the piechart above, the flight purpose with the highest risk is flights for personal use. This could be indicative on a lack of proper training in decision making in emergency situations by pilots flying aircrafts for personal purposes.  As such, we would recommend for additional pilot training in this areas.

# Conclusion
Based purely on the accident counts in this dataset, the aircraft categories with the lowest recorded incidents are: ULTR, Rocket, Powered-Lift, Blimp, WSFT, Ultralight, Powered Parachute, Weight-Shift, Gyrocraf, Balloon.
For this reason, we would advise the company to look at these aircraft categories first as an investment option.

However, it's important to note that while these categories have the fewest accidents in this dataset, this does not definitively mean they are the "lowest risk" without considering operational data such as the number of aircraft in service or total flight hours for each category. However, within the scope of this dataset, they show the least frequent involvement in reported accidents.

We can see that aircrafts made by Cessna and Piper have the highest count of reported accidents which could be attributed to their widespread use as they are popular and large aircraft manufacturers in the aviation industry. Other well known and large manufacturers of aircrafts with high accident rates are Bell, Boeing and Beech.
However, compared to Cessna and Piper,  Bell, Boeing and Beech have significantly lower accident rate over the same period of time.
All the makes with the least number of recorded accident in the dataset are comprised of a variety of names which mostly appear to be from less known aircraft manufacturers.

Although these makes have the least reported number of accidents, it may not be indicative of their overall safety, it may merely suggest that these are highly specialized aircrafts built by individuals and not many of them are operational, thereby leading to low reported cases of accidents.

# Recommendations
Recommendations for the head of Aviation:
1. Prioritize low-risk aircraft categories.
* Based on accident counts and fatality rates, aircraft such as ultralights, gliders, balloons, and powered parachutes show the lowest recorded accident frequency. These categories are safer entry points for new aviation ventures.
2. Focus on pilot training.
* A significant number of accidents occur during Takeoff and landing phases. Investing in advanced pilot training can greatly reduce risk.

3. Assess flight purpose risks
* Identify purpose of flight with high-risk — such as personal or instructional operations — to focus safety initiatives and training where they’ll have the greatest impact. In this case since most aircaraft accidents are linked to flying for personal purposes, pilots flying for this purpose could be trained on better decision-making and situational awareness as well as additional training on handling emergency situations.

4. Obtain exposure data.
* This will provide more operational data that would be useful in the analysis and give a clearer understanding of accident rates and hence more accurate risk comparisons.

# Setup
The easiest way to run this code is to upload and run it in google colab. Alternatively , if you would like to run it on your local computer you should install jupyter notebook and import the above listed libraries to be able to run the code. The data is included in this repository. Kindly download the data and load it in the desired environment to be able to run the code efficiently.

# Contact Details
If you would like to contribute to this project (be it reporting a bug, correcting a code or proposing a new approach altogether) feel free to reach out. If you run into problems while running this code or need clarification on how to run this code feel free to reach out to me. contact details: Github: NjorogeWinnie
