## Setconsolemode

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleMode(IntPtr hConsoleHandle,
   uint dwMode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/setconsolemode)
