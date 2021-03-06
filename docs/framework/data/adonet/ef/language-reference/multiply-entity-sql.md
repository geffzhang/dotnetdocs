---
description: "Learn more about: * (Multiply) (Entity SQL)"
title: "* (Multiply) (Entity SQL)"
ms.date: "03/30/2017"
ms.assetid: 508ce246-4e86-47dd-a605-4af4bebb9891
---
# * (Multiply) (Entity SQL)

Multiplies two expressions.  
  
## Syntax  
  
```sql  
expression * expression  
```  
  
## Arguments  

 `expression`  
 Any valid expression of any one of the numeric data types.  
  
## Result Types  

 The data type that results from the implicit type promotion of the two arguments. For more information about implicit type promotion, see [Type System](type-system-entity-sql.md).  
  
## Example  

 The following Entity SQL query uses the * arithmetic operator to multiply two numbers. The query is based on the AdventureWorks Sales Model. To compile and run this query, follow these steps:  
  
1. Follow the procedure in [How to: Execute a Query that Returns StructuralType Results](../how-to-execute-a-query-that-returns-structuraltype-results.md).  
  
2. Pass the following query as an argument to the `ExecuteStructuralTypeQuery` method:  
  
 [!code-sql[DP EntityServices Concepts#MULTIPLY](~/samples/snippets/tsql/VS_Snippets_Data/dp entityservices concepts/tsql/entitysql.sql#multiply)]  
  
## See also

- [Entity SQL Reference](entity-sql-reference.md)
