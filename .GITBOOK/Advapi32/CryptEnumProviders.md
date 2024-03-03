## CryptEnumProviders

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptEnumProviders(
   uint dwIndex,
   IntPtr pdwReserved,
   uint dwFlags,
   ref uint pdwProvType,
   StringBuilder pszProvName,
   ref uint pcbProvName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptenumprovidersa)
