## CryptSetAsyncParam

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSetAsyncParam(
   IntPtr hAsyncCryptProv,
   uint dwAsyncParam,
   IntPtr pbData,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetasyncparam)
