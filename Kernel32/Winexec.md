## Winexec

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint WinExec(string lpCmdLine,
   uint uCmdShow
);
```

[Microsoft documentation](TODO)
