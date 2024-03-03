## SQLGetDiagField

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLGetDiagField(
   SQLSMALLINT HandleType,
   IntPtr Handle,
   SQLSMALLINT RecNumber,
   SQLSMALLINT DiagIdentifier,
   IntPtr DiagInfo,
   SQLSMALLINT BufferLength,
   out SQLSMALLINT StringLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlgetdiagfield-function)
