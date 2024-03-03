## NetJoinDomain

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetJoinDomain(
   string lpServer,
   string lpDomain,
   string lpAccountOU,
   string lpAccount,
   string lpPassword,
   JoinOptions fJoinOptions
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmjoin/nf-lmjoin-netjoindomain)
