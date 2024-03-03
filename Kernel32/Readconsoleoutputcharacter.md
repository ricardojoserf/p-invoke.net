## Readconsoleoutputcharacter

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadConsoleOutputCharacter(IntPtr hConsoleOutput,
   [Out] StringBuilder lpCharacter,
   uint nLength,
   COORD dwReadCoord,
   out uint lpNumberOfCharsRead
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/readconsoleoutputcharacter)
