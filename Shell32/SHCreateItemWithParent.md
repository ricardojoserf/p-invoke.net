## SHCreateItemWithParent

```
[DllImport("shell32.dll")]
public static extern int SHCreateItemWithParent(
   IntPtr pidlParent,
   IntPtr psfParent,
   IntPtr pidl,
   ref Guid riid,
   out IntPtr ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nf-shobjidl_core-shcreateitemwithparent)
