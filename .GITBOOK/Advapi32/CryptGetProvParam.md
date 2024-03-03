## CryptGetProvParam

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptGetProvParam(
   IntPtr hProv,
   uint dwParam,
   IntPtr pbData,
   ref uint pdwDataLen,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetprovparam)
