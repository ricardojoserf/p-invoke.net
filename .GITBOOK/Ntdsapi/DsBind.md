## DsBind

```
[DllImport("ntdsapi.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int DsBind(
   string DomainControllerName,
   string DnsDomainName,
   out IntPtr phDS
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntdsapi/nf-ntdsapi-dsbindw)
