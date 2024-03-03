## Writeconsoleoutputcharacter

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteConsoleOutputCharacter(IntPtr hConsoleOutput,
   string lpCharacter,
   uint nLength,
   COORD dwWriteCoord,
   out uint lpNumberOfCharsWritten
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/writeconsoleoutputcharacter)
