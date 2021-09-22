BNYM HRMS system is the central repository of all BNYM employees and ECIF is the centralized true source of all involved party.  ECIF used to get the employee id list from HRMS and store it into the DB2 databases This process is called ECIF acquisition. Apart from HRMS ECIF received feeds from 100+ system. The current process is divided into here formats
1.	Layout conversion/transformation: In This process the file from different system is converted to ECIF standard layout known as A01 layout
2.	Comparison: Compare the current day feed with previous day feed and generate Add, delete, and update transitions
3.	Update: In This process the transactions are finally applied to the system
Currently HRMS is working on a legacy platform and is facing many challenges and limitations To overcome these challenges HRMS system is migration to an entirely new oracle platform. For ECIF perspective, our employee file has changed and few layout changes.
1.	Layout of the file has changed a little to handle the same.
2.	Employee id changed from 9 char to 11 Chars but we will be acquiring only 9 characters.
3.	Phone number layout has changed. Earlier the numbers were received in the format xxx-xxx-xxxx i.e. standard USA format. Now we will be receiving unformatted plain phone numbers which we are going to reformat for old layout.
4.	Change in name. There were multi discrepancies raised by us in name.
a.	Shortened Name: Middle names were shortened
b.	Name Suffixes like Jr. Sr. III have been dropped

 


