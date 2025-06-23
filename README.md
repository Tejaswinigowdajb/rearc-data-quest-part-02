# rearc-data-quest-part-02
 Population Data API and Lambda

This Lambda function fetches U.S. population data from the DataUSA API:

📎 https://datausa.io/api/data?drilldowns=Nation&measures=Population

## What it Does

- Adds required `User-Agent` header 
- Fetches population data in JSON format
- Uploads it to the specified S3 bucket: `s3://rearc-data-quest-bls-01/population/`
- Filenames are timestamped with today's date

## Files Included

- lambda_function.py`: Main Lambda code
- lambda_function.zip`: Deployment package with `requests` library
- output_link.txt`: Link to uploaded JSON file

## ATTACHED THE ZIP FILE FOR LAMBDA_HANDLER.PY

[rearc-data-quest-5a83ceb5-3358-4237-af88-a4d282f2908f (1).zip](https://github.com/user-attachments/files/20847503/rearc-data-quest-5a83ceb5-3358-4237-af88-a4d282f2908f.1.zip)

[rearc-data-quest (1).zip](https://github.com/user-attachments/files/20847502/rearc-data-quest.1.zip)


## Output S3 LINK

[population_data_2025-06-21 (3).json](https://github.com/user-attachments/files/20857463/population_data_2025-06-21.3.json)


[s3://rearc-data-quest-bls-01/population/
](https://rearc-data-quest-bls-01.s3.eu-north-1.amazonaws.com/population/)

[https://rearc-data-quest-bls-01.s3.eu-north-1.amazonaws.com/population/population_data_2025-06-21.json
](https://rearc-data-quest-bls-01.s3.eu-north-1.amazonaws.com/population/population_data_2025-06-21.json)

