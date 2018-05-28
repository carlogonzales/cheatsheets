# PL/SQL

## BLOCK TYPES

### Anonymous

```sql
DECLARE -- optional 
   -- declarations here
BEGIN
   -- statements
EXCEPTIONS -- optional
   -- handle exception
END;
```

### Procedure

```sql
PROCEDURE [name]
IS
DECLARE -- optional
   -- declarations here
BEGIN
  -- statements
EXCEPTION -- optional
  -- handle exception
END;
```

### FUNCTION

```sql 
FUNCTION [name]
RETURN [datatype] IS
DECLARE -- optional
   -- declarations here
BEGIN
  -- statements
EXCEPTION --optional
  -- handle exception
END;
```
