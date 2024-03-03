## Setcurrentconsolefontex

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetCurrentConsoleFontEx(IntPtr hConsoleOutput,
   bool bMaximumWindow,
   ref CONSOLE_FONT_INFO_EX lpConsoleCurrentFontEx
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/setcurrentconsolefontex)
