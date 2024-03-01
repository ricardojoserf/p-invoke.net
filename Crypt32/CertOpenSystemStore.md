## CertOpenSystemStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertOpenSystemStore(
   IntPtr hProv,
   string szSubsystemProtocol
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certopensystemstore)
