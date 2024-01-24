## Overview

### The pipeline is designed to:

1.Extract data from Reddit using its API.

2.Store the raw data into an S3 bucket from Airflow.

3.Transform the data using AWS Glue and Amazon Athena.

4.Load the transformed data into Amazon Redshift for analytics and querying.


## Prerequisites

1.AWS Account with appropriate permissions for S3, Glue, Athena, and Redshift.

2.Reddit API credentials.

3.Docker Installation

4.Python 3.9 or higher
