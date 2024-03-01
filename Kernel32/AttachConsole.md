## AttachConsole

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AttachConsole(
   uint dwProcessId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/attachconsole)
