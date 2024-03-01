## GetCurrentConsoleFont

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCurrentConsoleFont(
   IntPtr hConsoleOutput,
   [MarshalAs(UnmanagedType.Bool)] bool bMaximumWindow,
   out CONSOLE_FONT_INFO lpConsoleCurrentFont
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getcurrentconsolefont)
