## GetConsoleDisplayMode

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleDisplayMode(
   out uint ModeFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsoledisplaymode)
