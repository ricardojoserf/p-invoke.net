## SQLAllocStmt

```
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLAllocStmt(
   IntPtr hdbc,
   out IntPtr phstmt
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlallocstmt-function)
