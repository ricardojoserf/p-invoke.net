## Writeconsoleoutput

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteConsoleOutput(IntPtr hConsoleOutput,
   CHAR_INFO[] lpBuffer,
   COORD dwBufferSize,
   COORD dwBufferCoord,
   ref SMALL_RECT lpWriteRegion
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/writeconsoleoutput)
