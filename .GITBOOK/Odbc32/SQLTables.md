## SQLTables

```csharp
[DllImport("odbc32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int SQLTables(
   IntPtr hstmt,
   IntPtr szTableQualifier,
   short cbTableQualifier,
   IntPtr szTableOwner,
   short cbTableOwner,
   IntPtr szTableName,
   short cbTableName,
   IntPtr szTableType,
   short cbTableType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqltables-function)
