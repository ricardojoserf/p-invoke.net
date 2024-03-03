## CertEnumSystemStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertEnumSystemStore(
   uint dwFlags,
   IntPtr pvSystemStoreLocation,
   IntPtr pPrevEnumContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certenumsystemstore)
