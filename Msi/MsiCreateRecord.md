## MsiCreateRecord

```
DllImport("msi.dll", CharSet = CharSet.Auto)
public static extern int MsiEnumProducts(
   int iProductIndex,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder lpProductBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msicreaterecord)
