# SuperStore
select *
from superstore
order by(price);

SELECT SUM(price)
from superstore;

select avg(price)
from superstore;

select count(item_name) 'Smart LED TV'
from superstore;

 select count(item_name) 'Robot Vacuum Cleaner'
 from superstore;
 
 select max(price)
 from superstore;
 
 select * from superstore
 order by(stock_quantity);
 
select * from superstore
order by(price);

select * from superstore
order by(average_rating);

select * from superstore
order by(item_name);
