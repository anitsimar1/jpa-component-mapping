# Component Mapping

In component mapping, we will map the dependent object as a component. An component is an object that is stored as an value rather than entity reference. This is mainly used if the dependent object doen't have primary key. It is used in case of composition (HAS-A relation), that is why it is termed as component.



## Demonstration of Component Mapping through Code

For this I have created one Customer Entity and on Embeddable Address class.

One Customer Repository for performing basic CRUD opreations.

Written Test Cases for all CRUD operations.

Use MySql Database for storing customer table.



### Commands Used in MySQL Workbench - 

use sys;

CREATE TABLE customer (
    id int PRIMARY KEY auto_increment,
    name varchar(20),
	city varchar(20),
    state varchar(20),
    country varchar(20),
    zipcode varchar(20)
);

select * from customer;
