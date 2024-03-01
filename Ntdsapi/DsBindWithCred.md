## DsBindWithCred

```
[DllImport("ntdsapi.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int DsBindWithCred(
   string DomainControllerName,
   string DnsDomainName,
   IntPtr AuthIdentity,
   out IntPtr phDS
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntdsapi/nf-ntdsapi-dsbindwithcredw)
