## StgCreatePropStg

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreatePropStg(
   IUnknown pUnk,
   ref Guid rfmtid,
   [MarshalAs(UnmanagedType.IUnknown)] out object pStgOpen,
   uint grfMode,
   uint dwStgFmt,
   out IPropertyStorage ppPropStg
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgcreatepropstg)
