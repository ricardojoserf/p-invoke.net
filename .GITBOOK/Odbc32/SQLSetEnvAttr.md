## SQLSetEnvAttr

```csharp
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLSetEnvAttr(
   IntPtr EnvironmentHandle,
   SQLINTEGER Attribute,
   IntPtr ValuePtr,
   SQLINTEGER StringLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlsetenvattr-function)
