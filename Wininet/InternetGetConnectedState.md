## InternetGetConnectedState

```
[DllImport("wininet.dll", SetLastError = true)]
public static extern bool InternetGetConnectedState(
   out uint lpdwFlags,
   uint dwReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetgetconnectedstate)
