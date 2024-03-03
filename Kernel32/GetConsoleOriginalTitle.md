## GetConsoleOriginalTitle

```csharp
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetConsoleOriginalTitle(
   StringBuilder lpConsoleTitle,
   uint nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsoleoriginaltitle)
