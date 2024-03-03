## CryptSetKeyParam

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSetKeyParam(
   IntPtr hKey,
   uint dwParam,
   byte[] pbData,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetkeyparam)
