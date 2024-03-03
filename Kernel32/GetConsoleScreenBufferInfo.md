## GetConsoleScreenBufferInfo

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleScreenBufferInfo(
   IntPtr hConsoleOutput,
   out CONSOLE_SCREEN_BUFFER_INFO lpConsoleScreenBufferInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolescreenbufferinfo)
