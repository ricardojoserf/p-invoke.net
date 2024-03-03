## CryptExportKey

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptExportKey(
   IntPtr hKey,
   IntPtr hExpKey,
   uint dwBlobType,
   uint dwFlags,
   IntPtr pbData,
   ref uint pdwDataLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptexportkey)
