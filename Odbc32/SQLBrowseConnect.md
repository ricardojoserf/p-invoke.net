## SQLBrowseConnect

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLBrowseConnect(
   IntPtr hdbc,
   IntPtr szConnStrIn,
   short cbConnStrIn,
   IntPtr szConnStrOut,
   short cbConnStrOutMax,
   out short pcbConnStrOut
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlbrowseconnect-function)
