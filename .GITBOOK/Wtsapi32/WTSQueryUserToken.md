## WTSQueryUserToken

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSQueryUserToken(
   uint SessionId,
   ref IntPtr phToken
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsqueryusertoken)
