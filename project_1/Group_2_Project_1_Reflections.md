# Reflections on the Earth and Environmental Data Science Project 1 from Group 2


## A. Report and reflections from Emmanuel Julius

### What Was Done

We were provided with datasets that contained various daily weather parameters from 2006 to 2080. The task was to come up with an analysis to address a scientific question from the data.

After data observations, a research question and specific objectives were developed to achieve the aim of answering the research question. I played a role in organising group activities, discussing ideas and perspectives from fellow members until consensus was reached.
The research question, specific objectives, and parameters of analysis were as follows: 

**Question:** “Under regional warming with rising atmospheric moisture, how does this translate into extreme precipitation changes?”

**Specific objectives:**  
- Investigating long-term trends in parameters  
- Assessing their linear correlations  
- Quantifying changes in extreme rainfall events  

**Parameters of interest to be used for analysis were selected:** **Temperature**, **Precipitation rate**, and **Specific humidity**.

The analysis and visualisation packages like NumPy, Pandas, Matplotlib, Seaborn, etc., were used for our analyses.

An exploratory analysis was performed to check missing values, duplicates, and to note and fix any unusual observations.

One of the unusual observations I noted was that the minimum values for Precipitation rate and Snowfall were **negative**. In a real sense, these are scalar quantities and cannot be negative. The values were inspected and, once found to be very small negative numbers, were corrected by setting them to zero. (Which is a standard procedure).
Descriptive statistics analyses, trend analysis, correlations between parameters, and extreme values analyses were then carried out.

The outcomes were various plots and correlation values, from which interpretations, discussions, and conclusions were made.
Finally, the code and a presentation were prepared and submitted for presentation and assessment. I was responsible for various stages of code preparation and the introductory part of the PowerPoint. After everyone was done with their parts, I was the one who handled the final mobilisation, organization and submission of the presentation slides and the code.

### Lessons Learnt

As a newcomer to the world of data science, everything was new and offered a rewarding experience. Writing code, selecting functions and commands, creating data visualisations, and overcoming challenges to ensure smooth operation, doing and redoing it to make it functional and smooth, all of this was incredibly valuable.

The most important thing I realised is that I have great potential to become a good data scientist, which will add value to my work as an environmental scientist, given that I come from an African context where data science is still a new discipline. I have datasets for Project 1 and now Project 2. I will use them to practise and enhance my competence, as I have genuinely enjoyed doing analyses.

I was worried that not having a background in coding would be a major challenge, but I realised it was fine. From the experience of Project 1, my expectations for Project 2 and the rest of the semester have changed completely. I can confidently say that taking Earth and Environmental Data Science as an optional module was the best decision I made.

I also had the opportunity to work with real-world data, share documents, and collaborate interactively with colleagues using Google Colab. Working in a multicultural team helped me sharpen my teamwork and improve my decision-making, especially when we discussed which research questions to pursue and which data to use.

### Conclusion

This project has been an incredible start to my career in data science and has strengthened my passion for applying these skills to tackle environmental issues in Africa and beyond.


## B. Report and reflections from Xinqi Xie

For Project 1, we have already completed the presentation. I will reflect on it personally from the following points.

First, Project 1 was the first group task for this module, and at the beginning, I was not very familiar with my group members. As a result, communication and collaboration within our group occurred relatively late, leading to insufficient time for final revisions. In future group assignments, I will be more proactive in communicating with team members early, considering that data has already been shared, and I now know how demanding it might get when you delay starting.

Second, in this project, we initially decided to study the relationships between three parameters: daily temperature, precipitation, and humidity. However, after coding, we found that the correlations among them were not significant, making it difficult to formulate a clear research question. This further contributed to uncertainty in direction and analysis. We then managed to reach a consensus after many trial analyses and deep discussions. Therefore, next time, I will consider the initial purpose of parameter selection more carefully, for example, by first conducting preliminary comparisons across all available conditions, then selecting parameters with greater confidence for further study.

Third, in this project, I was initially assigned to investigate the relationships between three pairs of variables: rainfall and temperature, rainfall and humidity, and humidity and temperature. Later, by supplementing with correlation coefficients, Spearman's coefficient, and Pearson's coefficient, I gradually gained a better appreciation for the intuitiveness and convenience of coding-based analysis. I have learned a lot from this project, and I believe the next assignments will further enhance my competence.


## C. Report and reflections from Qianhao Li

This project focused on the analysis of regional meteorological and hydrological characteristics. I was mainly responsible for the Pearson and Spearman correlation analysis of three variables: humidity, rainfall, and average temperature, as well as the analysis of extreme precipitation trends and intensity mutations. I also completed the corresponding PPT production and visualisation work. I assisted in completing the entire process of data pre-processing, code writing, model operation, result interpretation, and PPT layout, ensuring the smooth progress of the team's module. At the same time, I also discovered my own shortcomings during the process. The following is a summary of my work and reflections.

In the correlation analysis of meteorological elements, I first cleaned the raw data, eliminating missing and abnormal values, and unified the time scale to ensure data consistency. Based on the correlation coefficient and significance level, I determined the positive and negative correlation relationships and overall patterns between variables. In the extreme precipitation analysis section, I analysed the precipitation change trends and intensity mutation nodes through model verification, combined with the regional climate background, to sort out the characteristics, providing data support for the project conclusion. In terms of PPT production, I distilled the core methods and conclusions, simplified the text content, and strived for a clean and clear page layout, highlighting the analysis focus.

Through this work, I have clearly recognised my obvious shortcomings. On the one hand, the depth of the analysis results is insufficient, and there is a gap compared with other groups. The correlation coefficients of the three variables in this project are relatively low, the significance is weak, and the overall pattern is not obvious, making it difficult to expand the content of the report. The reason for this is that I only conducted an overall period analysis, without stratified research by season and rain type, and the analysis method was single. I did not supplement with more precise statistical methods, and when facing weak correlation results, I did not deeply interpret the causes based on professional knowledge, but simply stated the conclusions, making the content thin and lacking highlights. On the other hand, there are problems with the PPT layout and logic. The page information is piled up, the main and secondary points are not distinguished, the charts are used directly without optimisation, the key data is not highlighted, and the connection between the correlation analysis and extreme precipitation analysis sections is stiff, with the overall logic not being coherent, resulting in a poor presentation effect.

In response to the above problems, I have formulated corresponding improvement directions. In the future, before conducting data analysis, I will improve the analysis plan, add stratified and time period comparisons, enrich the analysis methods, actively explore the reasons behind the results, and enhance the depth of the content. When making PPTs, I will strictly follow the principle of one core point per page, optimise the presentation of charts, sort out the logic of sections, making the content more coherent and the key points clearer. At the same time, I will strengthen the planning in the early stage, predict the data results in advance, prepare alternative ideas, and avoid passive responses to problems. In addition, I will continue to consolidate my statistical analysis and code operation skills and solidify my professional foundation.

This practice has enabled me to master the basic analysis methods of meteorological and hydrological data, but it has also exposed my shortcomings in thought design, in-depth exploration, and result presentation. In the future, I will draw on this experience, seriously improve my deficiencies, enhance my data analysis and team collaboration abilities, and complete subsequent learning and practical tasks with a more rigorous and complete attitude.


## D. Report and reflections from Xinhao Zhou

### 1. Python Skills Development

Over the three-week project time, I have grown from a coding beginner to being able to handle some easy and real environmental datasets. Based on the provided data, focus on cleaning and statistical analysis.
Firstly, mastering Pandas and Data Pre-processing. Through labs and lectures, I mastered key Pandas functionalities, practising how Pandas is used in data analysis. I learned how to transform raw daily environmental datasets into annual aggregates using Pandas group-by operations, which significantly improved my understanding of temporal scaling in climate analysis.
Do not handle missing values, which are common in sensor data, ensuring the scientific integrity of our conclusions. Cleaning data is necessary.
Secondly, time-Series structure analysis. Environmental data follows the time. I used pd. to_datetime () and resample() to convert raw data into annually or monthly averages for trend analysis. When dealing with gridded climate data, I realised that tabular tools like Pandas are sometimes insufficient. By learning Xarray, I mastered indexing data via named dimensions (e.g., lat, lon, time). This "label-aware" approach significantly reduced coding errors during spatial. Let me know how to deal with multi-dimensional data with Xarray.
Finally, beyond simple plots, I moved beyond basic line charts to using Seaborn for correlation heatmaps to visualise relationships between weather factors. What is more, I learned to choose colour blind friendly and perceptually uniform colourmaps to ensure my figures were both accurate and easy to find relationships.

### 2. Defining scientific questions 

As a Master’s student in Environmental Science, I initially thought this project was just about writing code. However, the core requirement was to make effective use of the data we already have to address a scientific question which proposed.
During the early stages, our group conducted literature research to justify why our chosen question was important. I learned that: Data-Driven Hypotheses: Analysis must stem from a scientific hypothesis (e.g., spatial patterns of warming reasons) rather than just processing numbers for the sake of it.

### 3. Challenges

One of the main challenges in this project was interpreting highly variable climate data. While the warming trend in temperature was clear and statistically significant, precipitation showed strong interannual fluctuations. These large year-to-year variations made it difficult to identify a clear long-term linear trend, especially for extreme precipitation events. At several points, we had to reconsider whether an apparent pattern was meaningful or simply a result of short-term variability.
Another challenge was understanding the statistical results beyond simply reporting numbers. Initially, it was tempting to assume that increasing temperature and humidity would automatically lead to increasing precipitation. However, our correlation and regression analyses revealed a weak or even negative relationship between temperature and mean precipitation, such as atmospheric circulation or dynamic constraints, rather than relying on thermodynamic reasoning.
We became more aware of the importance of careful data processing.
Finally, presenting complex statistical findings in a clear and logical way was another challenge. It required balancing scientific accuracy with clear communication, especially when explaining why increased atmospheric moisture did not translate into increased mean precipitation. 
Also, there are strict presentation rules: all members must present, and reading from notes or phones is forbidden. So, I practised translating complex Python logic into a scientific story that a general environmental audience could understand.

### 4. Limitations and Scientific Responsibility

Despite the meaningful insights got, this study has some limitations.
First, the analysis is based on a single regional dataset over the 2006–2080 projection period. The conclusions are therefore scenario-dependent and may not represent all possible ways of climate change. Different emission scenarios or alternative model outputs could produce different precipitation responses.
Second, the use of annual averages may mask important seasonal or short-term variations. Precipitation processes are often highly seasonal and driven by specific atmospheric circulation patterns. By aggregating the data to annual means, some important annual dynamics may not be fully captured or ignored.

### 5. Conclusion and Future Improvement

Project 1 in EART60702 was a journey of "computer language thinking." I am now viewing Python not just as a tool, but as a language to "talk" to environmental data. Although my learning of Python is just beginning, the project 1 provided the foundation to explore Python more in Project 2.