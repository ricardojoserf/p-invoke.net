## StgOpenPropStg

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenPropStg(
   IUnknown pUnk,
   ref Guid fmtid,
   uint grfMode,
   uint grfFlags,
   out IPropertyStorage ppPropStg
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgopenpropstg)
