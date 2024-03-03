## NetRenameMachineInDomain

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetRenameMachineInDomain(
   string lpServer,
   string lpNewMachineName,
   string lpAccount,
   string lpPassword,
   RenameOptions fRenameOptions
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmjoin/nf-lmjoin-netrenamemachineindomain)
