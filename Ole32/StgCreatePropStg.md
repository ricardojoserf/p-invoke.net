## StgCreatePropStg

```
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

Microsoft documentation: (TODO)
