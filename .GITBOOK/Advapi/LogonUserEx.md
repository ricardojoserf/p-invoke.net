## LogonUserEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LogonUserEx(
   string lpszUsername,
   string lpszDomain,
   string lpszPassword,
   uint dwLogonType,
   uint dwLogonProvider,
   out IntPtr phToken,
   out IntPtr ppLogonSid,
   out IntPtr ppProfileBuffer,
   out uint pdwProfileLength,
   out QUOTA_LIMITS pQuotaLimits
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonuserexa)
