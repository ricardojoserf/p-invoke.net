## LogonUser

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LogonUser(
   string lpszUsername,
   string lpszDomain,
   string lpszPassword,
   uint dwLogonType,
   uint dwLogonProvider,
   out IntPtr phToken
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonusera)
