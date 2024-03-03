## WNetCancelConnection2

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetCancelConnection2(
   string lpszName,
   uint dwFlags,
   bool fForce
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetcancelconnection2a)
