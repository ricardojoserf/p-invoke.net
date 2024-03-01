## NetGetDCName

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetGetDCName(
   string ServerName,
   string DomainName,
   out IntPtr Buffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netgetdcname)
