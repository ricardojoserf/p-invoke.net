## DsGetDcOpen

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsGetDcOpen(
   string DnsName,
   uint OptionFlags,
   string SiteName,
   IntPtr DomainGuid,
   string DnsForestName,
   uint DcFlags,
   out IntPtr GetDcContextHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsgetdcopenw)
