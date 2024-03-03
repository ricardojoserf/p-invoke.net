## CryptUninstallDefaultContextA

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptUninstallDefaultContextA(
   uint dwProvType,
   uint dwFlags,
   IntPtr pdwReserved,
   uint dwIndex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptuninstalldefaultcontext)
