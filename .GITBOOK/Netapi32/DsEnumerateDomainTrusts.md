## DsEnumerateDomainTrusts

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsEnumerateDomainTrusts(
   string ServerName,
   uint Flags,
   out IntPtr Domains,
   out uint DomainCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsenumeratedomaintrustsw)
