## SQLGetData

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLGetData(
   IntPtr hstmt,
   short iCol,
   SQL_C TargetType,
   IntPtr TargetValue,
   int BufferLength,
   out int StrLen_or_Ind
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlgetdata-function)
