## MsiEnumProductsEx

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiEnumProductsEx(
   [MarshalAs(UnmanagedType.LPTStr)] string szProductCode,
   [MarshalAs(UnmanagedType.LPTStr)] string szUserSid,
   uint dwContext,
   uint dwIndex,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpProductBuf
);
```

Microsoft documentation: (TODO)
