[![author](https://img.shields.io/badge/author-brunovn-red.svg)](www.linkedin.com/in/brunovn) 
[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-MIT-blue.svg)]

# pyyne_data_eng_test
Repository intended for Pyyne's data engineering testing.


# The Challange
You have been provided with a dataset (movie_metadata.csv). Your task is to
demonstrate your data engineering expertise by addressing the following
questions clearly and methodically. Please structure your response in
clear notebook format (Jupyter Notebook or variant), clearly outlining
your thought process, assumptions, and rationale in markdown.

# Solution Steps

**1. Data Loading**

Describe how you would load and initially inspect the provided dataset.
Explain the steps you'd take to ensure the data has loaded correctly.

**2. Initial Data Quality Assessment**

Examine the dataset to identify potential data quality issues or anomalies that
may affect the accuracy or usability of analyses. Clearly explain the
issues you discover and their potential implications.

**3. Numeric Data Consistency**

Evaluate the consistency and accuracy of numeric columns within the dataset.
Discuss any issues identified and explain your approach to resolving
them to ensure consistency for analytical purposes.

**4. Data Integrity and Duplicates**

Discuss your methodology for identifying and addressing duplicates or integrity
issues within the dataset. Clearly articulate your reasoning and the
steps you'd follow to handle these issues.

**5. Data Enrichment**

Describe your approach to enriching the dataset with external sources (such as
historical data, additional ratings, or reference information). 
Provide practical examples of external data sources you might use and explain how you'd integrate
them.

**6. Data Transformation and Standardization**

Identify potential columns that may require standardization or normalization.
Discuss when and why you would apply these transformations and their
potential impact on data analysis.

**7. Pipeline Design**

Outline your approach for designing a robust data pipeline capable of
continuous ingestion, cleaning, and quality maintenance for datasets
like the one provided. Explain your design choices and considerations.

**8. Bonus Challenge Question - Actor Collaboration and Performance Analysis**

Create an approach for generating an adjacency matrix representing co-acting
frequencies between actors. 
Demonstrate and explain how you would create
an adjacency matrix based on co-acting performance, measured by IMDb scores. 
Describe how
you'd visualize the top-performing actor pairs and run a correlation analysis between actor-pair likes and IMDb scores. 
Lastly, outline your method for identifying the largest co-acting group, considering direct or indirect connections between actors.