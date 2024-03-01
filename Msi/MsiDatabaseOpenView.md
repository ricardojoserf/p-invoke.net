## MsiDatabaseOpenView

```
DllImport("msi.dll", CharSet = CharSet.Auto)
public static extern int MsiEnumRelatedProducts(
   [MarshalAs(
   UnmanagedType.LPTStr)] string lpUpgradeCode,
   int dwReserved,
   int iProductIndex,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder lpProductBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msidatabaseopenvieww)
