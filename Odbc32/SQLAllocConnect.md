## SQLAllocConnect

```csharp
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLAllocConnect(
   IntPtr hEnv,
   out IntPtr phdbc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlallocconnect-function)
