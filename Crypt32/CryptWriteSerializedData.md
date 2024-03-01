## CryptWriteSerializedData

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptWriteSerializedData(
   IntPtr hStore,
   uint dwFlags,
   IntPtr pvStructInfo,
   byte[] pbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptwriteserializeddata)
