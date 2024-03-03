## DsGetDomainControllerInfo

```
[DllImport("ntdsapi.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int DsGetDomainControllerInfo(
   IntPtr hDS,
   string DomainName,
   DS_DOMAIN_INFO_LEVEL InfoLevel,
   out IntPtr pDCI
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntdsapi/nf-ntdsapi-dsgetdomaincontrollerinfow)
