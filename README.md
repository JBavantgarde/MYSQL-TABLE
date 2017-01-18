# MYSQL-TABLE
First table
mysql> create table actors ( ActorID INT NOT NULL AUTO_INCREMENT
    -> , first_name varchar(100) null
    -> , last_name varchar(100) null
    -> , primary key (ActorID));
Query OK, 0 rows affected (0.01 sec)

mysql> create table movies ( MovieID int not null auto_increment
    -> , title varchar(100) null
    -> , release_year int null
    -> , rating varchar(100) null
    -> , primary key(MovieID));
                                                          
Query OK, 0 rows affected (0.01 sec)
