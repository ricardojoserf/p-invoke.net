## MsiOpenProduct

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiOpenProduct(
   [MarshalAs(UnmanagedType.LPTStr)] string szProduct,
   out IntPtr hProduct
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msiopenproductw)
