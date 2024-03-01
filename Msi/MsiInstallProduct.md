## MsiInstallProduct

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiInstallProduct(
   [MarshalAs(UnmanagedType.LPTStr)] string szPackagePath,
   [MarshalAs(UnmanagedType.LPTStr)] string szCommandLine
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msiinstallproductw)
