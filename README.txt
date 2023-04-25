# CS4347_TeamMedic_SQL_Database
Team Medic Data Generation – ReadMe


Turn in a copy of the script or program used to generate the population. If a script or program was not used, describe how the data was entered.


For table Services, and its subset classes Consultation, Prescription, and Vaccination, we used the online data generator mockaroo to populate the table we used the online data generator mockaroo to download as a .sql file to satisfy and populate our database.

For table Payment, and its subset classes Insurance, RxCoupons, and SelfPay, and multivalued attribute SP_PayMethod we used the online data generator mockaroo to download as a .sql file to satisfy and populate our database.

For table Health Professionals, and its subset classes Doctor, Nurse, and Pharmacist, we used the online data generator mockaroo to download as a .sql file to satisfy and populate our database.

The file named SQL (Payment and services with subclasses).docx contains the data for following tables Services, Consultation, Prescription, Vaccination, Payment, Insurance, RxCoupons, and SelfPay, that we generated in Mockaroo and updated the tables as needed using Microsoft Word’s replace command in order to satisfy the conditions to our database. It also contains a multivalued attribute SP_PayMethod that we generated in Microsoft Excel, converted it to CSV file and later to SQL file.

For tables DeathCertificate, HP_Titles,  PR_Allergies, Pat_PhoneNums, SP_PayMethod we used the online data generator mockaroo to download as a .csv file and updated the file as needed, then converted it to a .sql file to satisfy and populate our database.

For Patient table, we used Mockaroo to download as a .csv file and updated the file as needed, then converted it to a .sql file to satisfy and populate our database.

For the following tables: Authorize, ConsistOf, Lookup, Provides, and Visit, we used Mockaroo to download as a .csv file and updated the file as needed, then converted it to a .sql file to satisfy and populate our database. 

For the following tables: Hospital, Clinic, Pharmacy, we used Mockaroo to download as a .csv file and updated the file as needed, then converted it to a .sql file to satisfy and populate our database. 

For the Institution table, in order to satisfy and populate the table we have various resources and websites. We first used Mockaroo as a foundation for the column names and downloaded it as a .csv file. In order to satisfy the ‘VitalCheckUp’ table we used the websites mentioned on the last page of the document. We then updated the .csv file as needed, ad lasted converted it to a .sql file to satisfy and populate our database. 

For the PatientRecord Table, in order to satisfy and populate the table we have used various resources and websites. We first used Mockaroo as a foundation for the column names and downloaded it as a .csv file. In order to satisfy the ‘Disease” table we used the website mentioned on the last page of the document. We then updated the .csv file as needed, and lasted converted it to a .sql file to satisfy and populate our database.


Work Cited

Mockaroo: https://www.mockaroo.com

Convert CSV: https://www.convertcsv.com/csv-to-sql.htm 

Institution Resource Websites:
•	Name of Institutions: https://data.cms.gov/provider-data/topics/hospitals 
•	VitalCheckUp
o	Heart Rate & Body Temp: https://www.openintro.org/data/index.php?data=thermometry 
o	Blood Pressure: https://github.com/Opensourcefordatascience/Datasets/blob/master/blood_pressure.csv 
PatientRecord Resource Webite:
•	Disease: https://www.thehealthsite.com/list-of-diseases-and-conditions/ 
