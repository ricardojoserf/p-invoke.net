## SQLDriverConnect

```
[DllImport("odbc32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int SQLDriverConnect(
   IntPtr hdbc,
   IntPtr hwnd,
   IntPtr szConnStrIn,
   short cbConnStrIn,
   IntPtr szConnStrOut,
   short cbConnStrOutMax,
   out short pcbConnStrOut,
   SQL_DRIVER_CONNECT fDriverCompletion
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqldriverconnect-function)
