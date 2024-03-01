## PROV_ENUMALGS_EX

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool PROV_ENUMALGS_EX(
   uint hProv,
   uint dwFlags,
   IntPtr pbData,
   ref uint pcbData,
   uint dwBufLen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-provenumalgsex)
