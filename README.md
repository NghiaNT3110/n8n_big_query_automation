# Data Automation Pipeline for GA4 & BigQuery
- Description: In BigQuery Free Tier, data is only retained for 60 days, and the Scheduled Query feature requires a paid upgrade. To address this, I built an automated workflow using n8n that performs ETL from Google Analytics 4 (GA4) to BigQuery and automatically updates the dataset twice a month.

- Key Benefits:
  + Cost-saving: No need for BigQuery's paid Scheduled Query, leveraging the Free Tier instead. Also self-hosted n8n has no cost. 
  + Always up-to-date data: Prevents data loss due to the 60-day retention limit, with bi-monthly updates.
  + Flexible automation: Can be expanded to ETL data from multiple sources.

- Demo Data Sources: 
  + bigquery-public-data.ga4_obfuscated_sample_ecommerce.events_*
  + firebase-public-project.analytics_153293282.events_*

# Demo Image
  ![image](https://github.com/user-attachments/assets/0424d3d1-3643-4cef-afc2-94166e4d969a)

