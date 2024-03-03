## WNetUseConnection

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetUseConnection(
   IntPtr hwndOwner,
   ref NETRESOURCE lpNetResource,
   string lpPassword,
   string lpUserID,
   uint dwFlags,
   StringBuilder lpAccessName,
   ref int lpBufferSize,
   out uint lpResult
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetuseconnectiona)
