---
description: "updateDouble Method (java.lang.String, double)"
title: "updateDouble Method (java.lang.String, double) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: reference
apiname: 
  - "SQLServerResultSet.updateDouble (java.lang.String, double)"
apilocation: 
  - "sqljdbc.jar"
apitype: "Assembly"
ms.assetid: f70971d5-34cc-4f70-8a91-5d46356b24ae
author: David-Engel
ms.author: v-davidengel
---
# updateDouble Method (java.lang.String, double)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Updates the designated column with a **double** value given the column name.  
  
## Syntax  
  
```  
  
public void updateDouble(java.lang.String columnName,  
                         double x)  
```  
  
#### Parameters  
 *columnName*  
  
 A **String** that contains the column name.  
  
 *x*  
  
 A **double** value.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This updateDouble method is specified by the updateDouble method in the java.sql.ResultSet interface.  
  
## See Also  
 [updateDouble Method &#40;SQLServerResultSet&#41;](../../../connect/jdbc/reference/updatedouble-method-sqlserverresultset.md)   
 [SQLServerResultSet Members](../../../connect/jdbc/reference/sqlserverresultset-members.md)   
 [SQLServerResultSet Class](../../../connect/jdbc/reference/sqlserverresultset-class.md)  
  
  
