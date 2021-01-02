# Bash Script Project [ITI]
This project is Mini DBMS using Bash Script, consists of three levels each level has some scripts to apply some functionality
![DB](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pngkit.com%2Fbigpic%2Fu2w7r5t4a9w7r5t4%2F&psig=AOvVaw2MhmrpN9i_xcJaWyyQg-u3&ust=1609708130118000&source=images&cd=vfe&ved=2ahUKEwj9ncmblP7tAhVYwIUKHfwjBAkQr4kDegQIARB-)
![Bash](https://www.google.com/url?sa=i&url=https%3A%2F%2Fdevdojo.com%2Fbobbyiliev%2Fexecuting-bash-script-on-multiple-remote-server&psig=AOvVaw1TzGFKEHwJqXeORjdHRZkE&ust=1609708352820000&source=images&cd=vfe&ved=2ahUKEwjK5-GFlf7tAhXa0YUKHak1BbkQr4kDegUIARDGAQ)
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
- user able to open a specific table from DB which chosen at level#1

### Level#3   [called record level]
- user able to insert a new record inside a table which chosen at level#2
- user able to delete a record from a table which chosen at level#2
- user able to update a specific record inside a table which chosen at level#2

### Notes
- Data Type either INT or STRING only
- Each table has a PK and it is auto increment
- Project consists of two directory one for operation called "scripts" and the second for Database storage called "DBs" 

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

