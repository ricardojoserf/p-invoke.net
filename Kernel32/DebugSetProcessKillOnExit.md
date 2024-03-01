## DebugSetProcessKillOnExit

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DebugSetProcessKillOnExit(
   [MarshalAs(
   UnmanagedType.Bool)] bool KillOnExit
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-debugsetprocesskillonexit)
