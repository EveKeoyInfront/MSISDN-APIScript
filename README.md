# README #

### ABOUT SCRIPT ###
This is a script that reads from MSISDN list, processes it with Moli API, returns the processed details, and tabulate the result.
The processed result is a summary overviewing key details of MSISDN, http statuses of API, and login eligibility for each modules.

### SETUP ###

* npm run setup

### BEFORE RUN SCRIPT ###

* Create two folders: testData , result
* place .csv file in ./testData folder
* msisdn is a REQUIRED param in .csv file. Other param are optional.
* .csv file is case sensitive. Example:

msisdn,telco,id,remark

60123456789,CELCOM,010101229999,remark:Postpaid80

601987654321,DIGI

### RUN SCRIPT ###

* node read CsvFileName APIName
