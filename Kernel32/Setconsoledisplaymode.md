## Setconsoledisplaymode

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleDisplayMode(IntPtr hConsoleOutput,
   uint dwFlags,
   out COORD lpNewScreenBufferDimensions
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/setconsoledisplaymode)
