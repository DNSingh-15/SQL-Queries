## Queries for mssql in Azure Data Studio


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

### 2. Insert data into a table 
```
INSERT INTO dbo.employee (ID, Name, Type, Profession)
VALUES 
(2, 'Shubham', 'Text', 'Writer'),
(3, 'hublal', 'Text', 'Nothing')
```

### 3. Read Query data from a Table
```
SELECT * FROM employee;
```