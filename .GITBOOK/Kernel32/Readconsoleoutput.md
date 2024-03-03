## Readconsoleoutput

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadConsoleOutput(IntPtr hConsoleOutput,
   [Out] CHAR_INFO[] lpBuffer,
   COORD dwBufferSize,
   COORD dwBufferCoord,
   ref SMALL_RECT lpReadRegion
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/readconsoleoutput)
