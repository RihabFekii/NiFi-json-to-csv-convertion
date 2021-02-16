## Converting JSON to CSV with Apache NiFi 

###### ConvertRecord

**ConvertRecord** converts records from one data format to another using configured Record Reader and Record Write Controller Services. The Reader and Writer must be configured with “matching” schemas. By this, we mean the schemas must have the same field names.
Since we want to convert JSON to CSV then we will need to use **JsonTreeReader** as a Record Reader and **CSVRecordSetWriter**

###### Template overview

![alt text](https://github.com/RihabFekii/NiFi_JSON_To_CSV_Convertion/blob/main/Template.png)

For more details check this article: https://rihab-feki.medium.com/converting-json-to-csv-with-apache-nifi-a9899ca3f24b
