## Setconsolefont

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleFont(IntPtr hConsoleOutput,
   uint nFont
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/console/setcurrentconsolefontex)
