## WNetAddConnection2

```csharp
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetAddConnection2(
   ref NETRESOURCE lpNetResource,
   string lpPassword,
   string lpUserName,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetaddconnection2a)
