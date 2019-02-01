# INFO7210_DWBI_Assignment3
PART 1:
Two employee tables with the following columns were created to hold male and female employees data.
                      first name, last name, domain, login
 
The DDL script was generated using the Generate DDl Script option on the toolbar.

PART 2:
Built an SSIS package to read the employee table and split the records based on gender. The package started with dropping and recreating the destination table to avoid record duplication.
For Gender wise Split DFT, first we need to join the records from [HumanResources].[Employee] and [Person].[Person] to have all the desired columns. Once we have all the columns including unsplit LoginID, the loginid and domain are split in two columns and only those columns are mapped for gender wise split output.
 
 

PART 3 & 4:
As the changes to the original data table i.e [HumanResources].[Employee] were not permissible, similar DFT as part 2 was created and then an SQL Task to insert an abnormal record was executed. This gave us the abnormality in the table for us to validate the Gender Lookup process.

 


PART 5:
BCP Out
BCP In:
Created table in SQL to insert the records from Flat File
Ran the command prompt
 


PART 6:
The sql to find all the titles with more than one author.



PART 7:
The sql to show all the authors with more than one book

 

PART 8:
The sql to show the publishers with no titles




