# Twitter-Data-Pipeline-using-Airflow
## Overview: 
The project "Twitter Data Pipeline using Airflow" is aimed at building a robust and scalable data pipeline that retrieves and processes Twitter data using Apache Airflow. Twitter is a popular social media platform with a wealth of real-time data that can be leveraged for various analytical and business purposes.

The project involves setting up an Apache Airflow environment, which is a powerful open-source platform for orchestrating and managing workflows. Airflow allows us to define and schedule tasks, create dependencies, and monitor the execution of the data pipeline.

The pipeline retrieves Twitter data using the Twitter API, leveraging the Tweepy library for easy integration. The data extraction process can include various parameters such as hashtags, user profiles, likes, dislikes allowing us to fetch relevant tweets based on our requirements.

Once the data is collected, it undergoes preprocessing and transformation steps to clean and structure it for further analysis. This involves removing duplicates, handling missing values, normalizing text, extracting specific features of interest. After preprocessing, the data is stored in S3 buckets.

The entire pipeline is orchestrated and managed using Apache Airflow, which provides a visual interface for defining workflows, scheduling tasks, and monitoring the execution of the pipeline. Airflow's robustness and scalability ensure the pipeline can handle large volumes of data and adapt to changing requirements.

The implemented Twitter Data Pipeline using Airflow has been successfully deployed and has proven to be a valuable tool for organizations and individuals seeking to harness the power of Twitter data. It enables real-time monitoring, sentiment analysis, trend analysis, social media monitoring, and other data-driven applications that rely on Twitter data.

The project showcases the capabilities of Apache Airflow in building reliable and efficient data pipelines for Twitter data. It provides a foundation for organizations to leverage Twitter as a valuable data source and gain insights for various business and analytical purposes.

## Architecture:

![Screenshot 102351](https://github.com/NiteshChintawar/Twitter-Data-Pipeline-using-Airflow/assets/61157441/dc23a486-487e-486f-b08a-97d924bd7fc1)

## Code:

![Screenshot (106)](https://github.com/NiteshChintawar/Twitter-Data-Pipeline-using-Airflow/assets/61157441/a32e0bfb-51cb-4097-87bc-45144d691f04)

## Airflow:

![Screenshot (105)](https://github.com/NiteshChintawar/Twitter-Data-Pipeline-using-Airflow/assets/61157441/0ff9370d-af78-4cf9-9ba9-f3840c189908)

![Screenshot (104)](https://github.com/NiteshChintawar/Twitter-Data-Pipeline-using-Airflow/assets/61157441/d3880a1e-dcb0-4935-abe7-9db82893f213)

## Result:

[joerogan_refined_tweets.csv](https://github.com/NiteshChintawar/Twitter-Data-Pipeline-using-Airflow/files/11523466/joerogan_refined_tweets.csv)
