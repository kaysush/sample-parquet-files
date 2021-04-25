# Parquet Files
This repository hosts sample parquet files from [here](https://github.com/Teradata/kylo/tree/master/samples/sample-data/parquet).

I have made following changes : 
- Removed `registration_dttm` field because of its type `INT96` being incompatible with Avro. 
- Subsituted null for `ip_address` for some records to setup data for filtering. 
