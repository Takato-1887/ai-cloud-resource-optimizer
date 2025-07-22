# ai-cloud-resource-optimizer
AI-Driven Resource Optimization Framework using Google Cluster Data on AWS


Borg Traces Kaggle Project
Dataset Description
This project utilizes the Google Borg Compute Clusters Workload Traces 2019 dataset, which contains a comprehensive record of job submissions, scheduling decisions, and resource usage data for eight Google clusters in May 2019.

Key Features

Job Submissions: Every job submission is recorded, including job metadata and resource requests.
Scheduling Decisions: Detailed information about scheduling decisions, including alloc set reservations and job-parent relationships.
Resource Usage: CPU usage information histograms for each 5-minute period, providing a more accurate representation of resource utilization.
Job-Parent Relationships: Master/worker relationships, such as those found in MapReduce jobs, are also included.


Dataset Availability
The dataset is available via Google BigQuery, allowing for sophisticated analyses without the need for local resources. Reference:https://www.kaggle.com/datasets/derrickmwiti/google-2019-cluster-sample

Project Goals
Explore changes in workload variance and resource utilization since 2011.
Analyze the impact of additional data, such as CPU usage histograms and alloc set reservations.
Develop insights into cluster scheduling and resource management.
