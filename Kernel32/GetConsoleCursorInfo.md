## GetConsoleCursorInfo

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleCursorInfo(
   IntPtr hConsoleOutput,
   out CONSOLE_CURSOR_INFO lpConsoleCursorInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolecursorinfo)
