Book Recommendation System - Databricks Pipeline
I built a complete data pipeline for a book recommendation system using Databricks. The project implements a modern data architecture with:
Bronze → Silver → Gold pipeline structure for data processing and transformation
Analytical views for top 10 books by popularity score with time period filtering
Author analytics and rating analysis for comprehensive insights
Flexible time-based filtering (last year, 2 years, all-time) as required by business requirements
Tech stack: Databricks, Spark SQL, Delta Lake, Python
The pipeline processes data from Books.csv, Ratings.csv, and Users.csv files, transforming raw data into business-ready analytics views that power the recommendation engine. The solution includes proper data quality checks, schema management, and scalable architecture for production deployment.
