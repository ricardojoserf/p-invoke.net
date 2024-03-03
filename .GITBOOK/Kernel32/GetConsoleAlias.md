## GetConsoleAlias

```
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetConsoleAlias(
   string Source,
   StringBuilder TargetBuffer,
   uint TargetBufferLength,
   string ExeName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolealias)
