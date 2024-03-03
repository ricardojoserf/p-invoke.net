## SQLColAttribute

```csharp
[DllImport("odbc32.dll", SetLastError = true)]
public static extern int SQLColAttribute(
   IntPtr StatementHandle,
   short ColumnNumber,
   short FieldIdentifier,
   IntPtr CharacterAttribute,
   short BufferLength,
   out short StringLength,
   out IntPtr NumericAttributePtr
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/sql/odbc/reference/syntax/sqlcolattribute-function)
