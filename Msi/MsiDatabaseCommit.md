## MsiDatabaseCommit

```
DllImport("msi.dll", CharSet = CharSet.Auto)
public static extern int MsiEnumProductsEx(
   [MarshalAs(
   UnmanagedType.LPTStr)] string szProductCode,
   [MarshalAs(
   UnmanagedType.LPTStr)] string szUserSid,
   IntPtr dwContext,
   int dwIndex,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder lpProductBuf,
   ref int pcchProductBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msidatabasecommit)
