## NetDfsMove

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetDfsMove(
   string DfsEntryPath,
   string NewDfsEntryPath,
   uint Flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmdfs/nf-lmdfs-netdfsmove)
