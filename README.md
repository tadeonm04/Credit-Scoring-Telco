The following project have the intention to help in feature selection for credit scoring prediction using telecom data using pyspark for ETL and pandas for processing. 

Traditional credit scores depend on loan repayments, and other financial behaviors recorded by credit bureaus. However, many individuals lack
sufficient credit history, making it difficult to assess their creditworthiness. Telco offers an alternative source for capturing patterns that
correlate with financial behavior. The objective is to engineer high-quality features to improve credit default prediction with the following
datasets:

Customer_attributes — 10,274 customers details and credit (part-00000-d027ba5a-8db5-4529-b0b9-3838a81ce68b-c000.snappy.parquet)
default label.
1. id: Unique user identifier (UUID).
2. region: Region identifier.
3. device: Mobile device brand and model.
4. default: Binary credit default label (1 for defaulter).



call_detail_record — 1,051,192 logs of telco transactions. (ALL THE REMAINING PARQUET FILES)
1. date: Event date as YYYYMMDD.
2. hour: Event hour as HH.
3. source_id: UUID that originated the event.
4. destination_id: UUID that received of event.
5. calls: Total number of calls made.
6. duration: Total duration of calls in seconds.
7. messages: Total number of SMS sent.
