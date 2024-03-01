## Writeconsole

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteConsole(IntPtr hConsoleOutput,
   [MarshalAs(UnmanagedType.LPArray)] byte[] lpBuffer,
   uint nNumberOfCharsToWrite,
   out uint lpNumberOfCharsWritten,
   IntPtr lpReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/writeconsole)
