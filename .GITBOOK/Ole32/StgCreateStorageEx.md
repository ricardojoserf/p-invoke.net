## StgCreateStorageEx

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreateStorageEx(
   [MarshalAs(UnmanagedType.LPWStr)] string pwcsName,
   uint grfMode,
   uint stgfmt,
   uint grfAttrs,
   ref STGOPTIONS pStgOptions,
   IntPtr reserved,
   ref Guid riid,
   out IStorage ppObjectOpen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgcreatestorageex)
