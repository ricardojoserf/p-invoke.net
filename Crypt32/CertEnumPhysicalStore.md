## CertEnumPhysicalStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertEnumPhysicalStore(
   IntPtr pvSystemStore,
   uint dwFlags,
   IntPtr pvArg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certenumphysicalstore)
