## CryptGetAsyncParam

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetAsyncParam(
   IntPtr hAsyncCryptProv,
   IntPtr phAsyncParam,
   IntPtr pbData,
   ref uint pcbData,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetasyncparam)
