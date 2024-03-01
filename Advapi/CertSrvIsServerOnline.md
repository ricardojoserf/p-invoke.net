## CertSrvIsServerOnline

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CertSrvIsServerOnline(
   string wszConfig
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/certsrv/nf-certsrv-certsrvisserveronline)
