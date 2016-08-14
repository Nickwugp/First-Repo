# Mysql
## this is my first repo for practicing sql syntax

**sugar database**

```sql
#dyigonoignosygun
create database test;
use test;
create table test1 (name char(10),
point int(3),
date date,
primary key (name)
);
load data local infile'D:\\testtxt1.txt' into table test1 fields terminated by '\t';
select * from test1 order by date asc;
```
* how to create table    
* how to select some columns  
* how to extract data from some table   


```sql
create table prod_cons(
monthly date not null,
prod_tot float(6,2),
cons_tot float(6,2),	
lv_tot float(6,2),
industore float(6,2),	
prod_cane float(6,2),	
cons_cane float(6,2),	
lv_cane	float(6,2),
prod_beet float(6,2),	
cons_beet float(6,2),
lv_beet float(6,2)
);
load data local infile'D:\\data\\prod_cons.txt' into table prod_cons fields terminated by '\t';
select * from spot_price;
select * from prod_cons;
```
*this is the syntax how the sugar database created*
