## SQLRowCount

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLRowCount(
   IntPtr StatementHandle,
   out int RowCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlrowcount-function)
