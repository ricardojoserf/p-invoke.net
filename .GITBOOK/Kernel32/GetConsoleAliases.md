## GetConsoleAliases

```csharp
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetConsoleAliases(
   StringBuilder[] AliasBuffer,
   uint AliasBufferLength,
   string ExeName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/getconsolealiases)
