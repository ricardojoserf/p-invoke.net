## WNetAddConnection3

```csharp
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetAddConnection3(
   IntPtr hwndOwner,
   ref NETRESOURCE lpNetResource,
   string lpPassword,
   string lpUserName,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetaddconnection3a)
