## GetCurrentConsoleFont

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCurrentConsoleFont(
   IntPtr hConsoleOutput,
   [MarshalAs(UnmanagedType.Bool)] bool bMaximumWindow,
   out CONSOLE_FONT_INFO lpConsoleCurrentFont
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getcurrentconsolefont)
