## StgCreatePropSetStg

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreatePropSetStg(
   IStorage pStorage,
   uint dwReserved,
   out IPropertySetStorage ppPropSetStg
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgcreatepropsetstg)
