---
layout: page
title: hospital data analysis- population health
description: Analyzing health system EMR data to inform SDOH measures
img: assets/img/pop_health.jpeg
importance: 1
category: healthcare
---


In this project, I analyzed a health system's data on bullet wound, drug-related visits and depression, suicide rates in three cities, namely Boston, Brockton and Worcester within a 3-year period. The data was analyzed using BigQuery. I also used PolicyMap to correlate the findings to:
- violent crime rates
- availability of addiction medicine management
- homelessness rates

This project was done to identify gaps in the three areas and to inform policy recommendations.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bullet_wound_race.png" title="Bullet Wound Visits, by race" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Bullet Wound Visits, studied by race in 3 cities
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bullet_wound_language.png" title="Bullet Wound Visits, by language" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Bullet Wound Visits, studied by language spoken by the patient, in 3 cities
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/drug_race.png" title="Drug-related Visits, by race" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drug-related Visits, studied by race, in 3 cities
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/drug_language.png" title="Drug-related Visits, by language" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drug-related Visits, studied by language spoken by the patient, in 3 cities
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/depression_suicide.png" title="Overall depression and suicide rates" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Depression-related visits and suicide rates, in 3 cities
</div>

The above images are the health system data analyzed, and these reasons for admission were correlated to violent crime rates, addiction medicine management facilities and homelessness in the 3 cities, using PolicyMap, in the same time period.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/violent_crime.png" title="Violent crime rates" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Violent Crime Rates, in 3 cities
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/addiction_med.png" title="Availability of Addiction Medicine Management" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Availability of Addiction Medicine Management, in 3 cities
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/homelessness.png" title="Rate of Homelessness" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Rate of homelessness, in 3 cities
</div>

In the above analysis, some noticeable points were:
- Predominant racial groups not represented in hospital admissions distribution, specifically in Brockton
Despite lower violent crime rate in Worcester, racial minorities and non-English speakers still experiencing comparable crime
In light of drug-related visits, Brockton stands out with the highest visit rate, signaling a significant issue in the city. Concerns also extend to French, Chinese, Italian, and Russian-speaking populations.

With these datapoints, the following are the recommendations for SDOH policies:
- Conduct thorough analysis in language-specific communities to identify crime rates, drug issues, access, and data discrepancies.
- Increase data granularity by partnering with census data to identify disparities on a more accurate level
- Improve racial and language diversity in Emergency services, public officials, for equitable awareness and access
- Implement outreach initiatives to connect individuals experiencing homelessness with essential services such as shelters, healthcare, and social support networks
- Addressing the service gaps in healthcare accessibility across all counties

