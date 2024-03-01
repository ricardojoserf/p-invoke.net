## NetUnjoinDomain

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUnjoinDomain(
   string lpServer,
   string lpAccount,
   string lpPassword,
   UnjoinOptions fUnjoinOptions
);
```

Microsoft documentation: (TODO)
