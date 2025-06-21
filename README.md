# rearc-data-quest-part-02
 Population Data API and Lambda

This Lambda function fetches U.S. population data from the DataUSA API:

📎 https://datausa.io/api/data?drilldowns=Nation&measures=Population

## What it Does

- Adds required `User-Agent` header (as per API rules)
- Fetches population data in JSON format
- Uploads it to the specified S3 bucket: `s3://rearc-data-quest-bls-01/population/`
- Filenames are timestamped with today's date (e.g., `population_data_2025-06-21.json`)

## Files Included

- lambda_function.py`: Main Lambda code
- lambda_function.zip`: Deployment package with `requests` library
- output_link.txt`: Link to uploaded JSON file

## ATTACHED THE ZIP FILE FOR LAMBDA_HANDLER.PY

[rearc-data-quest-5a83ceb5-3358-4237-af88-a4d282f2908f (1).zip](https://github.com/user-attachments/files/20847503/rearc-data-quest-5a83ceb5-3358-4237-af88-a4d282f2908f.1.zip)

[rearc-data-quest (1).zip](https://github.com/user-attachments/files/20847502/rearc-data-quest.1.zip)

## Output S3 LINK

s3://rearc-data-quest-bls-01/population/
