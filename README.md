# SQL Practices
This file includes my solutions to LeetCode SQL questions.

## Easy Questiosns
### Q175 Combine Two Tables
```sql
SELECT FirstName, LastName, City, State
FROM Person
LEFT JOIN Address
ON Person.PersonId = Address.PersonId
```
