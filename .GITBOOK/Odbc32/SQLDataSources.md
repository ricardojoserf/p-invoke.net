## SQLDataSources

```
[DllImport("odbc32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int SQLDataSources(
   IntPtr henv,
   ODBC_FETCH_DIRECTION Direction,
   StringBuilder ServerName,
   short BufferLength1,
   out short NameLength1Ptr,
   StringBuilder Description,
   short BufferLength2,
   out short NameLength2Ptr
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqldatasources-function)
