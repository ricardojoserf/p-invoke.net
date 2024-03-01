## PFXImportCertStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr PFXImportCertStore(
   ref CRYPT_DATA_BLOB pPFX,
   string szPassword,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-pfximportcertstore)
