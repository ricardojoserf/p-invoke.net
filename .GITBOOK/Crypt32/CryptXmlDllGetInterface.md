## CryptXmlDllGetInterface

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptXmlDllGetInterface(
   IntPtr pwszDll,
   IntPtr pwszInterface,
   ref IntPtr ppvImpl
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/cryptxml/nc-cryptxml-cryptxmldllgetinterface)
