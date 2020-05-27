# SQL  
### 1.INNER JOIN和LEFT JOIN的区别  
### 2.查询数据库中表的数量和名称、视图的数量和名称、存储过程的数量和名称;  
```
SELECT COUNT(*) FROM sys.objects WHERE type='U'   
SELECT name FROM sys.objects WHERE type='U'
```
```
SELECT COUNT(*) FROM sys.objects WHERE type='V'   
SELECT name FROM sys.objects WHERE type='V'
```
```
SELECT COUNT(*) FROM sys.objects WHERE type='P'   
SELECT name FROM sys.objects WHERE type='P'
```
