## WNetCancelConnection

```csharp
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetCancelConnection(
   string lpszName,
   bool fForce
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetcancelconnectiona)
