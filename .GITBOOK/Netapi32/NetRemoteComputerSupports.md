## NetRemoteComputerSupports

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetRemoteComputerSupports(
   string UncServerName,
   uint SupportLevel,
   uint SupportMask
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmremutl/nf-lmremutl-netremotecomputersupports)
