## CryptUnprotectData

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptUnprotectData(
   ref DATA_BLOB pDataIn,
   StringBuilder ppszDataDescr,
   ref DATA_BLOB pOptionalEntropy,
   IntPtr pvReserved,
   ref CRYPTPROTECT_PROMPTSTRUCT pPromptStruct,
   uint dwFlags,
   ref DATA_BLOB pDataOut
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dpapi/nf-dpapi-cryptunprotectdata)
