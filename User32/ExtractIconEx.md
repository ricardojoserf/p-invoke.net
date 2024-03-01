## ExtractIconEx

```
[DllImport("shell32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint ExtractIconExA(string lpszFile,
   int nIconIndex,
   IntPtr[] phiconLarge,
   IntPtr[] phiconSmall,
   uint nIcons
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extracticonexa)
