## MsiEnumPathesEx

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiEnumPathesEx(
   [MarshalAs(UnmanagedType.LPTStr)] string szProduct,
   [MarshalAs(UnmanagedType.LPTStr)] string szAttribute,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpValueBuf,
   ref int pcchValueBuf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msienumpatchesexw)
