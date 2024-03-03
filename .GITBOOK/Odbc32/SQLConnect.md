## SQLConnect

```csharp
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLConnect(
   IntPtr hdbc,
   IntPtr szDSN,
   short cbDSN,
   IntPtr szUID,
   short cbUID,
   IntPtr szAuthStr,
   short cbAuthStr
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlconnect-function)
