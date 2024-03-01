## NetRenameMachineInDomain

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetRenameMachineInDomain(
   string lpServer,
   string lpNewMachineName,
   string lpAccount,
   string lpPassword,
   RenameOptions fRenameOptions
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netrenamemachineindomain)
