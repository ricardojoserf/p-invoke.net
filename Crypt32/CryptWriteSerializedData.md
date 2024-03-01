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

Microsoft documentation: (TODO)
