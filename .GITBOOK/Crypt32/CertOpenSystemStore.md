## CertOpenSystemStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertOpenSystemStore(
   IntPtr hProv,
   string szSubsystemProtocol
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certopensystemstorea)
