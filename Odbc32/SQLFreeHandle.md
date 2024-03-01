## SQLFreeHandle

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLFreeHandle(
   SQL_HANDLE HandleType,
   IntPtr Handle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlfreehandle-function)
