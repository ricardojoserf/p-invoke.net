## ImpersonateLoggedOnUser

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool ImpersonateLoggedOnUser(
   IntPtr hToken
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-impersonateloggedonuser)
