## RegNotifyChangeKeyValue

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegNotifyChangeKeyValue(
   IntPtr hKey,
   [MarshalAs(
   UnmanagedType.Bool)] bool bWatchSubtree,
   uint dwNotifyFilter,
   IntPtr hEvent,
   [MarshalAs(
   UnmanagedType.Bool)] bool fAsynchronous
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regnotifychangekeyvalue)
