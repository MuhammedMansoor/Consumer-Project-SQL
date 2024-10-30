# Consumer-Project-SQL
SQL Project to analyse data of Atliq Hardwares
#Q1
>>Provide the list of markets in which customer "Atliq Exclusive" operates its
business in the APAC region.
##QUERY
select distinct market from dim_customer
where customer="Atliq Exclusive" and Region="APAC";
