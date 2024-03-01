## GetConsoleScreenBufferInfoEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleScreenBufferInfoEx(
   IntPtr hConsoleOutput,
   ref CONSOLE_SCREEN_BUFFER_INFOEX lpConsoleScreenBufferInfoEx
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolescreenbufferinfoex)
