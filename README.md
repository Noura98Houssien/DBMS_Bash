# Bash Script Project [ITI]
This project is Mini DBMS using Bash Script, consists of three levels each level has some scripts to apply some functionality

<table> 
  <tr>
    <td><img src="db.png" width=350   height=350></td>
    <td><img src="bash.jpg" width=350 height=350></td>
  </tr>
 </table>
 
### Level#1   [called DB level]
- user able to create a new database
- user able to open a specific database
- user able to view all databases
- user able to delete a specific database
- user able to write a query to done the above functions (Bonus)

   - **to create a new DB**
    ```git
          $ createdb database_name;   OR    $ CREATEDB database_name;
    ```
   - **to delete DB**
    ```git
          $ dropdb database_name;     OR    $ DROPDB database_name;
    ```
   - **to open DB**
    ```git
          $ opendb database_name;     OR    $ OPENDB database_name;
    ```
   - **to view all DB**
   ```git
         $ showdbs;                  OR    $ SHOWDBS;
   ```
### Level#2   [called table level]
- user able to create a new  table inside DB which chosen at level#1
- user able to delete a specific table from  DB which chosen at level#1
- user able to list all tables inside DB which chosen at level#1
- user able to show structure of a table from DB which chosen at level#1
- user able to open a specific table from DB which chosen at level#1

### Level#3   [called record level]
- user able to insert a new record inside a table which chosen at level#2
- user able to delete a record from a table which chosen at level#2
- user able to update a specific record inside a table which chosen at level#2
- user able to show content of specific table which chosen at level#2

### Notes
- Data Type either INT or STRING only
- Each table has a PK column called "ID" which is predefined with INT data type and auto increment
- Database name or column name shouldn't contain any special characters or start with number
- we use gsub function inside UpdateRecord script and doesn't work with all version of git.we use git with version 2.27.0 
- Project consists of two directory one for operation called "scripts" and the second for Database storage called "DBs" 
- when create new table there are two files created in DBs directory one to save the data ex: TableName and another hidden file       to save the metadata ex:.TableName
- each row in the file represent record ,and columns separated by ":"

# installation
clone this repo in your directory then change dir to scripts 
``` git
$ git clone https://github.com/mohabrabie/DBMS_Bash.git
$ cd scripts
```
to start the program run  level#1 script called lvl1
```git
$ ./lvl1
```

