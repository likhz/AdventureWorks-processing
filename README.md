# Adventure Works Processing

This is an **ETL(Extract, Transform and load)** Project using SSIS.
- This project uses Adventures Works Data to work. it is a corpus with multiple datasheets like purchases, orders, shipment etc. which has been broken down in this repo for further processing.
- It is a process where it splits the corpus into multiple Excel spreadsheets and delets the source data using SSIS.
- Post which it moves the data from a Table to multiple Excel spreadsheets based on different conditions.
- Uses Visual Studio SSIS for the development of this project.


> For splitting a large data set into multiple excel spreadsheets, a source file and a destination file are chosen in the data flow task
![image](https://github.com/likhz/ETL-and-SSIS/assets/98212542/90728ab2-5731-46a2-b2ba-f38f0d4c873e)

> After which source data is split into 5 different spreadsheets based on condition based on ShipmethodID and these are the different destination files.
![image](https://github.com/likhz/ETL-and-SSIS/assets/98212542/4fda785e-630c-420c-b9c2-11266ae5c19a)

![image](https://github.com/likhz/ETL-and-SSIS/assets/98212542/4faca55b-fff0-43a2-9b6b-b35a57292b41)

> Using Execute sql task  database created was deleted
> To move the data from a Table to multiple Excel spreadsheets based on a condition another data flow task is used.
![image](https://github.com/likhz/ETL-and-SSIS/assets/98212542/14b47fe0-e766-427b-892c-c9e3d148c219)

> Same data set is used as source here as well and using condition split data is split from a table to multiple spreadsheets.
![image](https://github.com/likhz/ETL-and-SSIS/assets/98212542/0272f266-b128-4f83-a408-982852ad2edf)

![image](https://github.com/likhz/ETL-and-SSIS/assets/98212542/f9c94190-c4d7-4469-8c0b-fd47d6300d27)




