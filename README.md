# Spotify-aws

In this Project I leveraged services like S3, Athena, Glue, Quicksight

Kaagle Link : https://shorturl.at/qBUX5
Processed Data : https://shorturl.at/biQUX

Here's a summary of my journey:

Amazon S3:

Staged the raw Spotify dataset efficiently in S3.
AWS Glue:

Leveraged Glue’s visual ETL capabilities to clean and transform the data.
Stored the processed data back in S3 for further use.
AWS Glue Crawler:

Created a Glue catalog table using a crawler to automatically detect the schema and make the data easily searchable.
Amazon Athena:

Queried the cataloged data directly from S3 using Athena’s powerful SQL interface.
Amazon QuickSight:

Analyzed the data and built interactive dashboards to visualize the insights from the Spotify dataset.
Challenges Faced:

QuickSight Table Detection Issue: Initially, QuickSight couldn’t detect the tables in my Glue catalog. After some investigation, I realized the problem was due to the services being in different AWS regions. Ensuring all services were in the same region resolved this issue, enabling seamless data visualization.
Key Takeaways:

Always ensure that interconnected AWS services are in the same region to avoid integration problems.
Properly configuring IAM roles and permissions is crucial for smooth service integration.
Utilizing Glue’s visual ETL simplifies the data transformation process, making it easier to handle complex datasets.
QuickSight is a powerful tool for deriving actionable insights from processed data.
This project was a fantastic learning experience, allowing me to enhance my data engineering and visualization skills. Excited to continue exploring and improving my data projects!
