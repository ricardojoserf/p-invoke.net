## DsMapSchemaGuids

```
[DllImport("ntdsapi.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int DsMapSchemaGuids(
   IntPtr hDS,
   int cGuids,
   Guid[] rgguid,
   out IntPtr ppGuidMap
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntdsapi/nf-ntdsapi-dsmapschemaguidsw)
