## CreateWellKnownSid

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateWellKnownSid(
   WELL_KNOWN_SID_TYPE WellKnownSidType,
   IntPtr DomainSid,
   IntPtr pSid,
   ref uint cbSid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-createwellknownsid)
