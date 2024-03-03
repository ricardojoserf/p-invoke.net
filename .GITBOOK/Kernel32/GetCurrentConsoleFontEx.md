## GetCurrentConsoleFontEx

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCurrentConsoleFontEx(
   IntPtr hConsoleOutput,
   [MarshalAs(UnmanagedType.Bool)] bool bMaximumWindow,
   ref CONSOLE_FONT_INFO_EX lpConsoleCurrentFont
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getcurrentconsolefontex)
