## DuplicateTokenEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DuplicateTokenEx(
   IntPtr hExistingToken,
   uint dwDesiredAccess,
   ref SECURITY_ATTRIBUTES lpTokenAttributes,
   uint ImpersonationLevel,
   uint TokenType,
   out IntPtr phNewToken
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-duplicatetokenex)
