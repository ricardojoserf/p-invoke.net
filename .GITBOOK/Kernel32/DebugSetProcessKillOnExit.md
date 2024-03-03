## DebugSetProcessKillOnExit

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DebugSetProcessKillOnExit(
   [MarshalAs(UnmanagedType.Bool)] bool KillOnExit
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-debugsetprocesskillonexit)
