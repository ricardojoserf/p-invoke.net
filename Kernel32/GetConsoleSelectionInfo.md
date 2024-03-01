## GetConsoleSelectionInfo

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleSelectionInfo(
   out CONSOLE_SELECTION_INFO lpConsoleSelectionInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getconsoleselectioninfo)
