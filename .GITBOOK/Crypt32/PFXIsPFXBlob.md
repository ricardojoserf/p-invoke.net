## PFXIsPFXBlob

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool PFXIsPFXBlob(
   ref CRYPT_DATA_BLOB pPFX
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-pfxispfxblob)
