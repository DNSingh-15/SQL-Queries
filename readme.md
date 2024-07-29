## Basic SQL Queries

### 1. create table 
```
IF OBJECT_ID('[dbo].[employee]', 'U') IS NOT NULL
DROP TABLE [dbo].[employee]
GO

CREATE TABLE [dbo].[employee]
(
    ID INT NOT NULL PRIMARY KEY,
    Name NVARCHAR(50) NOT NULL,
    Type NVARCHAR(50) NOT NULL,
    Profession NVARCHAR(200) NOT NULL,
);
GO
```

### 2. SELECT ( Read data )
```
SELECT * FROM employee;
SELECT FROM WHERE ORDER BY GROUP BY HAVIN.G LIMIT
```

### 3. INSERT 
```
INSERT INTO VALUES

INSERT INTO dbo.employee (ID, Name, Type, Profession)
VALUES 
(2, 'Shubham', 'Text', 'Writer'),
(3, 'hublal', 'Text', 'Nothing')
```

### 4. UPDATE
```
UPDATE tableName SET columnNmae = 0;
UPDATE tableName SET columnNmae = 0 WHERE userID = 123;
```

### 5. DELETE
```
DELETE FROM tableName WHERE ID = 123;  ==>> that row will be delete 
```

## Advanced SQL Queries

### 1. JOINS
![Alt Text](joins.png)


















