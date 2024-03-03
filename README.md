# News Pulse: Harnessing Bing API for Real-Time Insights
End to End Microsoft Fabric Analytics Project focusing on Bing News Sentiment and KPIs

Abstract:
In an age of information overload, real-time analysis of news sentiment is invaluable for decision-making across various domains. My project, "News Pulse: Harnessing Bing API for Real-Time Insights," presents a comprehensive end-to-end analytics solution that leverages the Bing News API to ingest, transform, and store news data. This data is then subjected to sentiment analysis using a pre-trained machine learning model, enabling the extraction of valuable insights regarding public opinion and sentiment trends.

![Screenshot (2)](https://github.com/19gcarpio/BingAnalytics/assets/92619560/e5303e90-96c5-423f-8783-8656b7a9cf07)

**Azure Environmental Setup:**
The project begins with the establishment of an Azure environment, leveraging Azure services such as Azure Virtual Machines, Azure Databricks, Azure Data Factory, Azure Blob Storage, and Azure Machine Learning. This setup provides a scalable and flexible infrastructure for deploying the entire data pipeline and machine learning models.

**Data Ingestion:**
Raw data from various sources, such as social media feeds, customer reviews, or sensor data, is ingested into the Azure environment. Azure Data Factory is utilized for orchestrating data pipelines, allowing for efficient and automated extraction of data from different sources.

**Data Transformation:**
Once the data is ingested, it undergoes transformation processes to clean, preprocess, and prepare it for analysis. Azure Databricks, with its Apache Spark-based processing capabilities, is employed for this purpose. Data transformation tasks include data normalization, feature engineering, and handling missing values.

**Data Storage:**
Processed data is stored in Azure Blob Storage or Azure Data Lake Storage for efficient storage and retrieval. These storage solutions offer scalability, security, and integration with other Azure services.

**Sentiment Analysis with Machine Learning:**
Machine learning models are developed and trained for sentiment analysis using Azure Machine Learning. Natural Language Processing (NLP) techniques are applied to analyze text data and determine sentiment polarity (positive, negative, neutral). Azure ML provides capabilities for model training, hyperparameter tuning, and model deployment.

**Interactive Power BI Dashboard:**
The insights derived from sentiment analysis are visualized through an interactive Power BI dashboard. Power BI connects directly to the Azure data sources, enabling real-time or scheduled updates of visualizations. The dashboard includes various visual elements such as charts, graphs, and maps to present sentiment trends and patterns in an intuitive manner.

**Orchestration:**
Azure Data Factory serves as the orchestrator for the entire data pipeline, coordinating data workflows, scheduling tasks, and monitoring pipeline performance. It ensures seamless execution of data ingestion, transformation, model training, and deployment processes.

**Testing and Validation:**
Testing and validation are crucial stages to ensure the accuracy and reliability of the entire data pipeline and machine learning models. Azure provides testing frameworks and services such as Azure DevOps for continuous integration and continuous deployment (CI/CD), Azure Monitor for monitoring pipeline performance, and Azure Databricks for testing model performance and accuracy against validation datasets. Comprehensive testing ensures that the deployed solution meets the required quality standards and delivers accurate sentiment analysis results.
