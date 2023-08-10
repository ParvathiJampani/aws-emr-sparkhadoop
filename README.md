# emr-spark-job-to-process-data


### Prerequisites:
1. Create S3 bucket named: big-_data_EMR
2. Create 3 folders inside: data-source, data-output, emr-logs
3. Get the souce data from https://insights.stackoverflow.com/survey
4. Create an IAM service role for EMR cluster

## Step by step process

1. Create an EMR Cluster and make sure port 22 is open in the security group
2. Create the script to be used for processing data
3. Run spark job to process data to s3
