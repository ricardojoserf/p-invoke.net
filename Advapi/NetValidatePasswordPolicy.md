## NetValidatePasswordPolicy

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint NetValidatePasswordPolicy(
   string ServerName,
   IntPtr Qualifier,
   IntPtr PolicyHandle,
   out uint pAuthenticators,
   ref IntPtr ppAuthenticators,
   out uint pCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lsalookup/nf-lsalookup-netvalidatepasswordpolicy)
