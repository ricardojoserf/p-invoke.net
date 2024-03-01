## GetModuleBaseName

```
[DllImport("psapi.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint GetModuleBaseName(
   IntPtr hProcess,
   IntPtr hModule,
   StringBuilder lpBaseName,
   uint nSize
);
```

Microsoft documentation: (TODO)
