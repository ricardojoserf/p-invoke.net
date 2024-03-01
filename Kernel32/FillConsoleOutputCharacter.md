## FillConsoleOutputCharacter

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FillConsoleOutputCharacter(
   IntPtr hConsoleOutput,
   char cCharacter,
   uint nLength,
   COORD dwWriteCoord,
   out uint lpNumberOfCharsWritten
);
```

Microsoft documentation: (TODO)
