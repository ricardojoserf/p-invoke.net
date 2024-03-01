## GetConsoleFontSize

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleFontSize(
   IntPtr hConsoleOutput,
   int nFont
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/getconsolefontsize)
