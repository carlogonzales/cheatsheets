# PL/SQL

## BLOCK TYPES

### Anonymous

```sql
DECLARE -- optional 
   -- declarations here
BEGIN
   -- statements
EXCEPTIONS -- optional
END;
```

### Procedure

```sql
PROCEDURE [name]
IS
DECLARE -- optional
BEGIN
  -- statements
EXCEPTION -- optional
END;
```

### FUNCTION

```sql 
FUNCTION [name]
RETURN [datatype] IS
DECLARE -- optional
BEGIN
  -- statements
EXCEPTION --optional
END;
```
