## GetSidSubAuthority

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern IntPtr GetSidSubAuthority(
   IntPtr pSid,
   uint nSubAuthority
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsidsubauthority)
