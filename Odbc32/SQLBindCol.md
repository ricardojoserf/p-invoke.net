## SQLBindCol

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLBindCol(
   IntPtr StatementHandle,
   short ColumnNumber,
   short TargetType,
   IntPtr TargetValue,
   int BufferLength,
   out int StrLen_or_Ind
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlbindcol-function)
