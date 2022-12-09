
# Revising the select query 1

Query all columns for all American cities in the **CITY** table with populations larger than 100000. The **CountryCode** for America is USA.

The **CITY** table is described as follows:

![question_image](images/1245.jpg)

```sql

SELECT * FROM CITY WHERE population>100000 and Countrycode='USA'

```

