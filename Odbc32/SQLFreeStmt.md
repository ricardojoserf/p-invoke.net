## SQLFreeStmt

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLFreeStmt(
   IntPtr hstmt,
   SQLUSMALLINT fOption
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlfreestmt-function)
