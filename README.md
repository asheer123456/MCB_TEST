# MCB_TEST
MCB Assessment Steps for Data Migration:
1.	Execute the file “DB_Prequisite.sql” which will enable you to create the table “XXBCM_ORDER_MGT” and inserts all the data.
2.	Execute the file “DB_Table” which will create the tables below : 
•	XXBCM_ORDER_MGT_CLR : Copy of table “XXBCM_ORDER_MGT” with all cleaned data(eg : remove o from amount to replace with 0)
•	XXBCM_SUPPLIER : Table contain all data about supplier 
•	XXBCM_TRANSACTION : Table contain all data about transactions
3.	Compile the package PCG_XXBCM_ORDER from the file PCG_XXBCM_ORDER.sql – This will enable you to create the procedures PROC_XXBCM_ORDER_CLEAR, PROC_XXBCM_SUPPLIER and PROC_XXBCM_TRANSACTION.
4.	Execute the file “DB_All_Data.sql” which will use the package and procedures create in step 3 to  insert data in the tables created in step2
5.	Execute the file “DB_Views” which will create the views DB_SUMMARY, DB_THIRD_HIGHEST and DB_SUPPLIER_LIST. 

TASK 4: execute the file “DB_SUMMARY.sql” – This will display the summary of Orders with their corresponding list of distinct invoices and their total amount.

TASK 5: execute the file “DB_THIRD_HIGHEST.sql” – This file will return details for the THIRD (3rd) highest Order Total Amount from the list.

TASK 6: execute the file “DB_SUPPLIER_LIST.sql” – This file will display the List all suppliers with their respective number of orders and total amount ordered from them between the period of 01 January 2017 and 31 August 2017

