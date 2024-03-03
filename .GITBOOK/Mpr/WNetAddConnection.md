## WNetAddConnection

```csharp
[DllImport("mpr.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint WNetAddConnection(
   string lpRemoteName,
   string lpPassword,
   string lpLocalName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetaddconnectionw)
