## SHCreateItemFromIDList

```csharp
[DllImport("shell32.dll")]
public static extern int SHCreateItemFromIDList(
   IntPtr pidl,
   ref Guid riid,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromidlist)
