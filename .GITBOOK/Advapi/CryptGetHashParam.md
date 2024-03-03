## CryptGetHashParam

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptGetHashParam(
   IntPtr hHash,
   uint dwParam,
   IntPtr pbData,
   ref uint pdwDataLen,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgethashparam)
