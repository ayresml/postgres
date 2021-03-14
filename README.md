# postgres
Notes on running postgres in Kali Linux

## postgres manual page https://www.postgresql.org/docs/

- Login in as yourself
- enter command : sudo su postgres
- enter command psql
- enter command: create database 'database name'
- enter \q to exit
- enter command psql 'database name'
- If already in psgl -> \c 'database name'

- COmMANDS
- CREATE TABLE tablename ( value1 type, value2 type );
- INSERT INTO tablename (value1, value2) VALUES (# , #);
- SELECT * FROM tablename -> gives the whole table print out.
- SELECT valueT1, value T2 FROM table1, table2 WHERE columnT1 = columnT2;
