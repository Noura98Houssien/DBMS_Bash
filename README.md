# Bash Script Project [ITI]
This project is Mini DBMS using Bash Script, consists of three levels each level has some scripts to apply some functionality
### Level#1   [called DB level]
- user able to create a new database
- user able to open a specific database
- user able to view all databases
- user able to delete a specific database
- user able to write a query to done the above functions (Bonus)
```bash
    - to create a new DB : createdb database_name;   OR    CREATEDB database_name;
    - to delete DB       : dropdb database_name;     OR    DROPDB database_name;
    - to open DB         : opendb database_name;     OR    OPENDB database_name;
    - to view all DB     : showdbs;                  OR    SHOWDBS;
```
### Level#2   [called table level]
- user able to create a new  table inside DB which chosen at level#1
- user able to delete a specific table from  DB which chosen at level#1
- user able to list all tables inside DB which chosen at level#1
- user able to open a specific table from DB which chosen at level#1

### Level#3   [called record level]
- user able to insert a new record inside a table which chosen at level#2
- user able to delete a record from a table which chosen at level#2
- user able to update a specific record inside a table which chosen at level#2

### Notes
- Data Type either INT or STRING only
- Each table has a PK and it is auto increment

# installation
clone this repo in your directory
``` 
$ git clone 
