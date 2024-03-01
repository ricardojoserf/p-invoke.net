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

[Microsoft documentation](TODO)
