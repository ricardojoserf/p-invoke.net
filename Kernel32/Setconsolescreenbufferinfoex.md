## Setconsolescreenbufferinfoex

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleScreenBufferInfoEx(IntPtr hConsoleOutput,
   ref CONSOLE_SCREEN_BUFFER_INFO_EX lpConsoleScreenBufferInfoEx
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolescreenbufferinfoex)
