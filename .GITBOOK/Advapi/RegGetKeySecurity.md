## RegGetKeySecurity

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegGetKeySecurity(
   IntPtr hKey,
   uint SecurityInformation,
   [Out] byte[] pSecurityDescriptor,
   ref uint lpcbSecurityDescriptor
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetkeysecurity)
