## DsGetDcSiteCoverage

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsGetDcSiteCoverage(
   string ServerName,
   out IntPtr EntryCount,
   out IntPtr SiteNames
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsgetdcsitecoveragew)
