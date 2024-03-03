## CertAlgIdToOID

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertAlgIdToOID(
   uint dwAlgId,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certalgidtooid)
