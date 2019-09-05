# wsp1-mysql
Intro till MySQL

## Starta Server

Kör igång Ubuntu

kör

  sudo service mysql restart
  sudo service apache2 restart


Om apache2 bråkar pga. port 80.

Starta services / tjänster i Windows.

Stoppa branchen och starta om apache2.

## mysql

**setup**
kör
     sudo mysql -u root

grant all privileges on *.* to 'jensny'@'localhost' identified by 'password';



Baskod

show database/table

`create -- || --`

`insert into `tablename`(fält) values`

SELECT fält(*) from 'tablename'


## Kod

**show** database; - Shows all databases

**create** database 'databasename'; - Creates new database

**use** 'databasename'; - Uses database

**show** tables; - Shows all tables

**create** table 'tablename' (id int unsigned auto_increment, primary key(id)) engine=innodb; - Creates new table and 1 collumn

**select** * from 'tablename' - Selects everything inside table

**alter** table 'tablename' add body varchar(255) not null; - Alter and add string to table

**describe** 'tablename'; - Shows what is in the table

**alter** table 'tablename' add created_at timestamp NULL, add updated_at timestamp NULL; - Add timestamp created_at and updated_at

**insert** into 'tablename' (body, created_at, updated_at, author) values ("", now(), now(), ""); -insert multiple into table
