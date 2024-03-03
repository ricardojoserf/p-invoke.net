## MsiGetProductInfo

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetProductInfo(
   [MarshalAs(UnmanagedType.LPTStr)] string szProduct,
   int dwUserSid,
   IntPtr pdwContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetproductinfow)
