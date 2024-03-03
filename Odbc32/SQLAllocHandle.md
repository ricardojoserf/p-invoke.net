## SQLAllocHandle

```csharp
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLAllocHandle(
   SQL_HANDLE HandleType,
   IntPtr InputHandle,
   out IntPtr OutputHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlallochandle-function)
