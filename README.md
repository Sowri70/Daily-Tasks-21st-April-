TASK - Data Cleaning and processing

To start with, CSV file is converted into an excel file formatting as a table.
The advantage of formatting it as a table is that it will dynamically get updated if one adds additional records/data.

With Power Query Editor in service, the following steps were taken:

Checked if there are any null values or duplicate records. Null value is replaced by zero.

Year_birth is changed to dob with DateTime

Replaced 2n Cycle to 2nd Cycle in education column

Income is shown as currency instead of integar

'acceptedcmp' columns are serially displayed as acceptedcmp1, acceptedcmp2....acceptedcmp5

All column headers were changed to lower case as it will be easier while working on SQL queries and for readibility.
