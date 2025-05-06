---
layout: page
title: Hospital Emergency Room Dashboard
description: My first Power BI project
img: assets/img/Hospital.jpg
importance: 3
category: work
---


## About this project
- For this project, I played a role as a BI Developer for a private hospital that specializes in providing comprehensive patient care with a key focus for enhancing its Emergency Room operations.<br>
- I created an interactive Power BI dashboard to enable stakeholders to track, analyze and make data-driven decisions regarding patient management and service optimizations. <br>

## The dataset

The dataset contains 9216 records from April 2023 to December 2024. It held details of patient's demographics such as name, age, gender, race...and their medical history data include: admission date, department referral, patient admin flag (whether admitted or not admitted), satisfaction score, wait time and case manager.
<br>


## Key Assumptions

In general, as a business analyst, I always like to communicate with stakeholders to  gather information about their requirements or understand their problems they need solutions for. In the absence of being able to chat with stakeholders in this project, I have made several assumptions which I used to guide my dashboard design. <br>

The primary goal for managers and stakeholders is viewing the history and current state of the Emergency Room in this hospital. So they can see what’s happening, understand why this is happening and decide how to make them better in terms of speed, quality and resources utilization. The key questions they want to answer are: <br>
- This dashboard aims to answer critical business questions for various stakeholders (Management, Marketing, Sales, Operations): <br>

 - What are the patient arrival patterns (by day, hour, month)? <br>
 - Are we meeting timeliness goals (e.g., % seen within 30 mins)? What is the average wait time? <br>
 - What are the key demographic characteristics of our ER patients (Age, Gender, Race)? <br>
 - What is the admission rate from the ER? <br>
 - Which departments are receiving frequent referrals from the ER, potentially indicating resource needs?<br>
 - How does performance trend month-over-month?<br>
 - Are there specific patient encounters or periods needing detailed review?<br>

<b>Key Performance Indicators (KPIs) & Metrics: </b>
<b>Primary Focus:</b> Number of Patients, Average Wait Time, Patient Satisfaction Score, Number of Patients Referred.
<b>Supporting Analyses:</b> % Patients Seen Within 30 Mins, Patient Admission Status (Admitted vs. Non-admitted), Patient distribution by Age, Gender, Race, Department Referral trends, Patient Volume by Day/Hour. <br>

## The dashboard

<b>Design Philosophy:</b> Developed using Power BI to provide an interactive and visual platform for ER performance analysis. The structure facilitates exploration from high-level summaries down to specific details.

<b>Monthly View:</b> Focuses on monitoring key metrics (like Admission Status, Age/Gender/Race Distribution, Timeliness, Referrals, Day/Hour Volume) on a month-by-month basis to identify trends and patterns for strategic improvement.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ER_1.png" title="Monthly View" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Consolidated View:</b> Offers a holistic performance summary using similar metrics as the Monthly View, but aggregated over a customizable date range selected by the user, allowing for flexible analysis periods.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ER_2.png" title="Consolidated View" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Patient Details:</b> Provides a granular, grid-based view of individual patient-level data (including ID, Name, Age, Race, Wait Time, Referral, Status, etc.) to enable detailed analysis and troubleshooting of specific cases or issues.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ER_3.png" title="Patient Details" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Key Takeaways:</b> Designed to synthesize findings from the other dashboards, presenting descriptive analysis, highlighting patterns or anomalies, and offering actionable recommendations to stakeholders for optimizing ER operations and patient care.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ER_4.png" title="Key Takeaways" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>


 <p><b>Meeting User Needs:</b> he dashboard directly addresses the stated business requirements by transforming raw ER data into visualized metrics and trends, enabling stakeholders to efficiently track performance against KPIs, understand operational dynamics, identify areas needing attention (like high wait times or referral bottlenecks), and make informed decisions to improve overall ER service delivery. </p>
