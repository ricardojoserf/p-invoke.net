## WSALookupServiceBegin

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSALookupServiceBegin(
   IntPtr qsRestrictions,
   uint dwControlFlags,
   ref IntPtr lphLookup
);
```

Microsoft documentation: (TODO)
