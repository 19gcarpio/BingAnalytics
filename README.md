# News Pulse: Harnessing Bing API for Real-Time Insights
End to End Microsoft Fabric Analytics Project focusing on Bing News Sentiment and KPIs

Abstract:
In an age of information overload, real-time analysis of news sentiment is invaluable for decision-making across various domains. My project, "News Pulse: Harnessing Bing API for Real-Time Insights," presents a comprehensive end-to-end analytics solution that leverages the Bing News API to ingest, transform, and store news data. This data is then subjected to sentiment analysis using a pre-trained machine learning model, enabling the extraction of valuable insights regarding public opinion and sentiment trends.

![Screenshot (2)](https://github.com/19gcarpio/BingAnalytics/assets/92619560/e5303e90-96c5-423f-8783-8656b7a9cf07)

**Project Overview:**

**1. Data Ingestion from Bing API using Data Factory:**
The analytics endeavor commences with the systematic extraction of data from external sources, facilitated by Azure Data Factory. Through the utilization of Data Factory, a seamless retrieval process ensues from the Bing API, establishing a robust cornerstone for subsequent analytical processes.

**2. Data Transformation using Synapse Data Engineering:**
Embarking on the process of data refinement, Synapse Data Engineering meticulously shapes raw JSON data into curated Delta Tables. Techniques such as incremental loading are employed to uphold process efficiency and ensure the generation of high-quality data outputs.

**3. Sentiment Analysis using Synapse Data Science:**
Leveraging the advanced capabilities of Synapse Data Science, sentiment analysis uncovers valuable insights from news descriptions. By accurately predicting sentiment classifications of news articles as Positive, Negative, or Neutral, this analysis provides actionable intelligence.

**4. Orchestration using Data Factory via pipelines:**
Mastering the orchestration of data workflows, Azure Data Factory pipelines ensure seamless operational flow. Through meticulous scheduling and management of data movement and processing tasks, operational efficiency is optimized.

**5. Data Reporting using Power BI:**
Empowering stakeholders with actionable insights, Power BI visually represents curated data. Crafted interactive reports and dashboards deliver compelling visualizations, facilitating informed decision-making processes.

**6. Configuring Alerts using the Data Activator:**
Demonstrating proactive vigilance, alerts and notifications are configured within Power BI visuals using the innovative Data Activator tool. Vigilant monitoring of key metrics and prompt addressing of anomalies upholds data integrity and ensures analytical efficacy.

**7. End to End Pipeline Testing:**
Comprehensive validation procedures meticulously test the integrity and performance of pipelines. From data ingestion through transformation to reporting, rigorous testing protocols affirm the reliability and accuracy of analytical outputs.
