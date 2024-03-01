## SQLGetDiagRec

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLGetDiagRec(
   SQLSMALLINT HandleType,
   IntPtr Handle,
   SQLSMALLINT RecNumber,
   IntPtr Sqlstate,
   out int NativeError,
   IntPtr MessageText,
   SQLSMALLINT BufferLength,
   out SQLSMALLINT TextLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlgetdiagrec-function)
