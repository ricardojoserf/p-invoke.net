## MsiReinstallProduct

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiReinstallProduct(
   [MarshalAs(UnmanagedType.LPTStr)] string szProduct,
   uint dwReinstallMode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msireinstallproductw)
