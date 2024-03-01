## Setconsoleicon

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleIcon(
   IntPtr hIcon
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsoleicon)
