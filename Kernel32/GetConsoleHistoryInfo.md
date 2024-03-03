## GetConsoleHistoryInfo

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleHistoryInfo(
   out CONSOLE_HISTORY_INFO lpConsoleHistoryInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolehistoryinfo)
