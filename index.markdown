---
layout: index
title: Home
---

# Understanding the Trends in Assault Crimes in San Francisco

Crime data is one of the most critical tools for understanding urban safety, allowing both law enforcement and residents to grasp the evolving patterns of criminal activity. In this analysis, we focus on assault crimes in San Francisco, drawing from data spanning multiple years. Assault crimes are particularly revealing because they can indicate broader societal changes—ranging from economic downturns to policy shifts, or even the impact of events like the COVID-19 pandemic.

Using interactive visualizations, heatmaps, and time-series analysis, we explore how assault incidents have evolved over time, identifying key patterns and potential causes behind these fluctuations.

Long-Term Trends: The Rise and Fall of Assault Incidents
A time-series analysis of reported assault crimes in San Francisco (Figure 1) shows that from 2010 to around 2018, the number of assaults remained relatively stable, fluctuating slightly but staying within the range of 10,000 to 12,000 incidents per year. However, starting in 2019, there was a sharp decline, which became particularly pronounced after 2020. By 2025, the number of recorded assaults had dropped dramatically, reaching the lowest levels in the dataset.

# Time Series Visualisation

Figure 1: The yearly trend of assault crimes in SF from 2010 to 2025. The number of incidents remained stable until 2018, followed by a significant decline, particularly post-2020.

This pattern raises key questions:

Why was there a steep decline post-2019?

Were certain areas more affected than others?

Can external events like the COVID-19 pandemic explain part of the trend?

To answer these, we dive deeper into spatial analysis and interactive visualizations.

<img src="TimeSeriesAssault.png" alt="Description" width="70%" height="400px">

# Heat Map Visualisation

Examining the heatmap visualization of assaults across San Francisco reveals distinct geographic patterns. Certain neighborhoods—such as the Tenderloin, Mission District, and SOMA—have consistently high concentrations of assault incidents. These areas have long been associated with higher crime rates due to socioeconomic factors, homelessness, and nightlife activity, which can lead to a greater number of violent interactions.

<iframe src="sf_assault_heatmap.html" width="70%" height="400px"></iframe>

# Bokeh Visualisation

The COVID-19 Pandemic (2020-2022)

Lockdowns and social distancing reduced nightlife activity, street interactions, and bar-related violence.

Many businesses shut down or transitioned to remote work, leading to fewer people in high-crime areas.

San Francisco's overall crime rates dropped in early 2020, a trend observed in other major cities as well.

Changes in Law Enforcement Policies

San Francisco has seen shifting policing strategies, including calls for reduced law enforcement presence in certain communities and reforms aimed at decriminalizing lower-level offenses.

The shift in focus away from aggressive policing may have influenced reporting patterns.

<iframe src="bokeh_assault_interactive.html" width="70%" height="400px"></iframe>

This analysis of assault crime trends in San Francisco reveals a relatively stable period until 2019, followed by a dramatic drop post-2020. The most affected areas—such as the Tenderloin and Mission District—highlight how geography and socioeconomic conditions influence crime rates. However, the impact of COVID-19, policy changes, and shifting city dynamics complicates the story, making it essential to continue monitoring trends in the coming years.

#References:

### Impact of the COVID-19 Pandemic on Crime Rates

1. _Public Policy Institute of California (PPIC)_ - Crime trends during the pandemic, including shifts in property and violent crime.

   - Source: [https://www.ppic.org/publication/crime-after-proposition-47-and-the-pandemic/](https://www.ppic.org/publication/crime-after-proposition-47-and-the-pandemic/)

2. _California Policy Lab_ - Analysis of crime trends in California during the COVID-19 pandemic.
   - Source: [https://capolicylab.org/wp-content/uploads/2021/09/Crime-in-California-During-the-Covid-19-Pandemic.pdf](https://capolicylab.org/wp-content/uploads/2021/09/Crime-in-California-During-the-Covid-19-Pandemic.pdf)

### Effect of Policy Changes on Crime Rates

3. _Proposition 47 and Its Impact on Crime Rates_ - Reclassification of certain offenses and its effect on crime trends.

   - Source: [https://www.ppic.org/publication/crime-after-proposition-47-and-the-pandemic/](https://www.ppic.org/publication/crime-after-proposition-47-and-the-pandemic/)

4. _Center on Juvenile and Criminal Justice (CJCJ)_ - Law enforcement spending vs. crime clearance rates.
   - Source: [https://www.cjcj.org/reports-publications/report/california-law-enforcement-agencies-are-spending-more-but-solving-fewer-crimes](https://www.cjcj.org/reports-publications/report/california-law-enforcement-agencies-are-spending-more-but-solving-fewer-crimes)

### Recent Crime Trends and Law Enforcement Efforts

5. _San Francisco Government Report_ - Decline in crime rates in 2024 due to new public safety measures.

   - Source: [https://www.sf.gov/news--san-francisco-2024-crime-rates-down-city-prepares-implement-new-voter-approved-public-safety](https://www.sf.gov/news--san-francisco-2024-crime-rates-down-city-prepares-implement-new-voter-approved-public-safety)

6. _San Francisco Police Department Reform Efforts_ - Eight-year reform completion and crime reduction.
   - Source: [https://www.sanfranciscopolice.org/news/sfpd-substantial-compliance-following-years-long-reform](https://www.sanfranciscopolice.org/news/sfpd-substantial-compliance-following-years-long-reform)

_Note:_ These sources provide credible evidence to support claims regarding the impact of COVID-19, policy changes, and law enforcement reforms on crime rates in San Francisco.
