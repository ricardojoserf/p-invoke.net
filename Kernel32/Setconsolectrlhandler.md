## Setconsolectrlhandler

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleCtrlHandler(
   ConsoleCtrlHandlerRoutine HandlerRoutine,
   bool Add
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolectrlhandler)
