#### See if you can leak the whole database. The flag is in [there](https://web.ctflearn.com/web4/) somewhere...
 
After going to the website, you are asked to give an input. This input would lead us to the flag. As the name of this challenge is basic injection, we get a hint that we are supposed to perform an SQL injection.  

The website has connectivity with a database. The records from his database are fetched using a query. In this website, the query can be assumed to be:

`SELECT * FROM Table WHERE Column = 'input' ;`
    
where ‘input’ is the input which we have to enter. This is the general format of a query. Moreover, we have to give the input in such a way that the entire database is printed as we don’t know where exactly the flag is. If we give the input as:

`input = 1' or '1' = '1`

Then the query will be:

`SELECT * FROM Table WHERE Column = ' 1' OR '1' = '1 ';`

The `column=’1’` equation may or may not be true, but `‘1’==’1’` will always be true. Thus, the query will fetch all the records in the database as the condition `‘1’==’1’` is true for all rows. The results will be displayed on the screen and you will see the flag.

Also note the use of quotations. They are used in such a way that the expression fits inside the defined format of the query.  
