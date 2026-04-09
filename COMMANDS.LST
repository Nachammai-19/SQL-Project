CREATE TABLE Online_Shopping19(Product_id int PRIMARY KEY,Product_Name varchar(25),Category varchar(25),Brand varchar(25),Price int,Stock int);

Table created.

SQL> INSERT INTO Online_Shopping19 VALUES(101,'Smartphone','Electronics','Apple',100000,125);

1 row created.

SQL> INSERT INTO Online_Shopping19 VALUES (102,'Kurti set','Fashion','Max',2000,20);

1 row created.

SQL> INSERT INTO Online_Shopping19 VALUES(103,'Watch','Fashion','Titan',5000,210);

1 row created.

SQL> INSERT INTO Online_Shopping19 VALUES(104,'Backpack','Bags','Skybags',1500,320);

1 row created.

SQL> INSERT INTO Online_Shopping19 VALUES(105,'Slippers','Fashion','Zudio',800,430);

1 row created.

SQL> INSERT INTO Online_Shopping19 VALUES(107,'Monitor','Electronics','Led',5000,560);

1 row created.

SQL> SET PAGES 100 LINES 100
SQL> SELECT * FROM Online_Shopping19;

PRODUCT_ID PRODUCT_NAME              CATEGORY                  BRAND                          PRICE 
---------- ------------------------- ------------------------- ------------------------- ---------- 
     STOCK                                                                                          
----------                                                                                          
       101 Smartphone                Electronics               Apple                         100000 
       125                                                                                          
                                                                                                    
       102 Kurti set                 Fashion                   Max                             2000 
        20                                                                                          
                                                                                                    
       103 Watch                     Fashion                   Titan                           5000 
       210                                                                                          
                                                                                                    
       104 Backpack                  Bags                      Skybags                         1500 
       320                                                                                          
                                                                                                    
       105 Slippers                  Fashion                   Zudio                            800 
       430                                                                                          
                                                                                                    
       107 Monitor                   Electronics               Led                             5000 
       560                                                                                          
                                                                                                    

6 rows selected.

SQL> SELECT Product_id,Product_Name FROM Online_Shopping19;

PRODUCT_ID PRODUCT_NAME                                                                             
---------- -------------------------                                                                
       101 Smartphone                                                                               
       102 Kurti set                                                                                
       103 Watch                                                                                    
       104 Backpack                                                                                 
       105 Slippers                                                                                 
       107 Monitor                                                                                  

6 rows selected.

SQL> UPDATE Online_Shopping19 SET  PRICE='2000' WHERE Product_id=104;

1 row updated.

SQL> DELETE FROM Online_Shopping19 WHERE Product_id=107;

1 row deleted.

SQL> SELECT * FROM Online_Shopping19 WHERE   PRICE >=2000;

PRODUCT_ID PRODUCT_NAME              CATEGORY                  BRAND                          PRICE 
---------- ------------------------- ------------------------- ------------------------- ---------- 
     STOCK                                                                                          
----------                                                                                          
       101 Smartphone                Electronics               Apple                         100000 
       125                                                                                          
                                                                                                    
       102 Kurti set                 Fashion                   Max                             2000 
        20                                                                                          
                                                                                                    
       103 Watch                     Fashion                   Titan                           5000 
       210                                                                                          
                                                                                                    
       104 Backpack                  Bags                      Skybags                         2000 
       320                                                                                          
                                                                                                    

SQL> SELECT * FROM Online_Shopping19 ORDER BY Stock DESC;

PRODUCT_ID PRODUCT_NAME              CATEGORY                  BRAND                          PRICE 
---------- ------------------------- ------------------------- ------------------------- ---------- 
     STOCK                                                                                          
----------                                                                                          
       105 Slippers                  Fashion                   Zudio                            800 
       430                                                                                          
                                                                                                    
       104 Backpack                  Bags                      Skybags                         2000 
       320                                                                                          
                                                                                                    
       103 Watch                     Fashion                   Titan                           5000 
       210                                                                                          
                                                                                                    
       101 Smartphone                Electronics               Apple                         100000 
       125                                                                                          
                                                                                                    
       102 Kurti set                 Fashion                   Max                             2000 
        20                                                                                          
                                                                                                    

SQL> ALTER TABLE Online_Shopping19 DROP COLUMN Stock;

Table altered.

SQL> ALTER TABLE Online_Shopping19 DROP COLUMN Category;

Table altered.

SQL> SELECT * FROM Online_Shopping19;

PRODUCT_ID PRODUCT_NAME              BRAND                          PRICE                           
---------- ------------------------- ------------------------- ----------                           
       101 Smartphone                Apple                         100000                           
       102 Kurti set                 Max                             2000                           
       103 Watch                     Titan                           5000                           
       104 Backpack                  Skybags                         2000                           
       105 Slippers                  Zudio                            800                           

SQL> TRUNCATE TABLE Online_Shopping19;

Table truncated.

SQL> SELECT * FROM Online_Shopping19;

no rows selected

SQL> DROP TABLE Online_Shopping19;

Table dropped.

SQL> 
