## Setconsolefont

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleFont(IntPtr hConsoleOutput,
   uint nFont
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setconsolefont)
