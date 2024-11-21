## Aggregate functions 
- count
- min
- max
- average
- sum

## Group By
- often used with count , min,max or sum
-  if grouping columns contains null value, all null values are grouped together

## Having 
order of execution
- group by
- apply aggregate conditions
- apply Having condition

### Select * from where G-H-O-L
- G : group by
- H : Having
- O : Order by
- L : Limit (has offset)

## JOIN
  - INNER JOIN :COMMON IN BOTH TABLES
  - LEFT JOIN : left table + common in tableB
  - RIGHT JOIN : common in table A + tableB
  - FULL OUTER JOIN : tableA+tableB
  - NATURAL JOIN : same as inner join

- INNER JOIN
     - select tableA.id,tableA.name,tableB.course
       from tableA
       inner join tableB
       on tableA.id = tableB.id
       NB : use alias for table names to shorten the query

- LEFT JOIN
     - select A.id,A.name,B.course
       from tableA A
       left join tableB B
       on A.id = B.id

- RIGHT JOIN
     - select A.id,A.name,B.course
       from tableA A
       right join tableB B
       on A.id = B.id
       
  - FULL OUTER JOIN
     -select A.id,A.name,B.course
       from tableA A
       right join tableB B
       on A.id = B.id
    
    - NATURAL JOIN
        - select *
          from tableA
          natural join tableB;

## NESTED QUERIES
  first inner query is executed then outer query
   IN, NOT IN, EXISTS,NOT EXISTS,ANY , ALL,COMPARISON OPERATORS

### CREATE,READ,UPDATE,DELETE
   - CREATE
     -  CREATE TABLE table_name(
         col1 col1_dtype,
         col2 col2_dtype,
        );

     - INSERT
       - INSERT INTO students ('id','name') VALUES('1','RAM')
   - UPDATE:
   - ALTER :
      - ALTER TABLE table_name
        ADD column_name datatype;
   - DELETE
   - DROP : 
      -DROP TABLE table_name;
   - TRUNCATE
    
        
