## GetConsoleSelectionInfo

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleSelectionInfo(
   out CONSOLE_SELECTION_INFO lpConsoleSelectionInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsoleselectioninfo)
