# Retail Analytics Project Example using Sqoop, HDFS, and Hive

Retail Analytics Project Example using Sqoop, HDFS, and Hive — Big Data project.

## Overview
Retail analytics is the process of delivering analytical data on inventory levels, supply chain movement, customer demand, sales, and other important factors for marketing and procurement choices. Demand and supply data analytics may be utilized to manage procurement levels as well as make marketing decisions. Retail analytics provides us with precise consumer insights and insights into the organization's business and procedures, as well as the scope and need for development. Aside from inventory management, many retailers employ analytics to determine customer patterns and shifting preferences by merging various sources. Businesses may discover developing trends, and better predict them by combining sales data with a range of criteria. This is strongly related to marketing functions, which also benefit from analytics. Companies may use retail analytics to strengthen their marketing strategies by better grasping individual preferences and gaining more detailed data. They may design str

## Data
The Walmart Store sales dataset consists of 6436 data points, including the following parameters:

- Store
- Date
- Weekly_Sales
- Holiday_Flag
- Temperature
- Fuel_Price
- CPI
- Unemployment

_Data is not included in this repository._

## Approach
- Containers for all the services are spun up using Docker.
- Setup for MySQL is performed for Table creation using the dataset.
- Data is imported using Sqoop into Hive.
- Data transformation is performed for analysis and reporting.

Key Takeaways
- Understanding the project and how to use AWS EC2 Instance
- Introduction to Docker
- Visualizing the complete Architecture of the system
- Usage of docker-composer and starting all tools
- Understanding HFDS and various file formats
- Understanding the use of different HDFS command
- Understanding Sqoop Jobs and valuable tools
- Introduction to Hive architecture
- Understanding Hive Joins and Views
- Performing various transformation tasks in Hive
- Setting up MySQL for table creation
- Migrating from RDBMS to Hive warehouse

Architecture

## Tech stack
➔ Language: SQL, Bash ➔ Services: AWS EC2, Docker, MySQL, Sqoop, Hive, HDFS

AWS EC2 A virtual server on Amazon's Elastic Compute Cloud (EC2) for executing applications on the Amazon Web Services (AWS) architecture is known as an Amazon EC2 instance. The Amazon Elastic Compute Cloud (EC2) service allows corporate customers to run application applications in a computer environment. Using Amazon EC2 eliminates the need to invest in hardware up front, allowing users to create and deploy apps quickly.

## How to run
Notebooks: [`presentation.ipynb`](Installation%20&%20Execution/presentation.ipynb)

## Project structure
```
.gitignore
Codes/
  docker-compose.yml
Installation & Execution/
  portforwarding.bat
  presentation.ipynb
README.md
```

## Credits
Based on a ProjectPro guided project.
