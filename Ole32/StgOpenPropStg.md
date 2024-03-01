## StgOpenPropStg

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenPropStg(
   IUnknown pUnk,
   ref Guid fmtid,
   uint grfMode,
   uint grfFlags,
   out IPropertyStorage ppPropStg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/propsys/nf-propsys-stgopenpropstg)
