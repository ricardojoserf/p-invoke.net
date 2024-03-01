## MsiDoAction

```
DllImport("msi.dll", CharSet = CharSet.Auto)
public static extern int MsiGetProductInfo(
   [MarshalAs(
   UnmanagedType.LPTStr)] string szProduct,
   [MarshalAs(
   UnmanagedType.LPTStr)] string szAttribute,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder lpValueBuf,
   ref int pcchValueBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msidoaction)
