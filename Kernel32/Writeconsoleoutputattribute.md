## Writeconsoleoutputattribute

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteConsoleOutputAttribute(IntPtr hConsoleOutput,
   ushort[] lpAttribute,
   uint nLength,
   COORD dwWriteCoord,
   out uint lpNumberOfAttrsWritten
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/writeconsoleoutputattribute)
