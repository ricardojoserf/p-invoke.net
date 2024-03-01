## DsGetDcName

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsGetDcName(
   string ComputerName,
   string DomainName,
   Guid DomainGuid,
   string SiteName,
   uint Flags,
   out IntPtr DomainControllerInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsgetdcnamew)
