## CertControlStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertControlStore(
   IntPtr hCertStore,
   uint dwFlags,
   uint dwCtrlType,
   IntPtr pvCtrlPara
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certcontrolstore)
