# Anonymize CSV

Reads an input CSV file, anonymizes any specified fields with a SHA1 hash and random salt, and copies the result to your clipboard. Can optionally write the result to an output CSV file instead. 


#### Example uses:
```
python run.py ~/my_data.csv --anonymize-fields full_name email_address
```

```
python run.py ~/my_data.csv --anonymize-fields full_name email_address --outfile ~/my_data_anonymized.csv
```
