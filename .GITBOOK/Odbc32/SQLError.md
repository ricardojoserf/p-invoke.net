## SQLError

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLError(
   IntPtr henv,
   IntPtr hdbc,
   IntPtr hstmt,
   StringBuilder szSqlState,
   out int pfNativeError,
   StringBuilder szErrorMsg,
   short cbErrorMsgMax,
   out short pcbErrorMsg
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlerror-function)
