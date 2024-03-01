## MsiOpenPackageEx

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiOpenPackageEx(
   [MarshalAs(UnmanagedType.LPTStr)] string szPackagePath,
   uint dwOptions,
   out IntPtr hProduct
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msiopenpackageexw)
