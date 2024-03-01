## CryptXmlDllGetInterface

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptXmlDllGetInterface(
   IntPtr pwszDll,
   IntPtr pwszInterface,
   ref IntPtr ppvImpl
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptxmldllgetinterface)
