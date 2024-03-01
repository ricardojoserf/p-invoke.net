## SQLExecDirect

```
[DllImport("odbc32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int SQLExecDirect(
   IntPtr hstmt,
   IntPtr szSqlStr,
   int cbSqlStr
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlexecdirect-function)
