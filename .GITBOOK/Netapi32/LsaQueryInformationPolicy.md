## LsaQueryInformationPolicy

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint LsaQueryInformationPolicy(
   IntPtr PolicyHandle,
   POLICY_INFORMATION_CLASS InformationClass,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaqueryinformationpolicy)
