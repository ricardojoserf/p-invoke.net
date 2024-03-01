## StgCreatePropSetStg

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreatePropSetStg(
   IStorage pStorage,
   uint dwReserved,
   out IPropertySetStorage ppPropSetStg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/propsys/nf-propsys-stgcreatepropsetstg)
