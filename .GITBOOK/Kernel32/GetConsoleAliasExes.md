## GetConsoleAliasExes

```csharp
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetConsoleAliasExes(
   StringBuilder[] ExeNameBuffer,
   uint ExeNameBufferLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolealiasexes)
