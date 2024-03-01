## GetConsoleMode

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleMode(
   IntPtr hConsoleHandle,
   out uint lpMode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getconsolemode)
