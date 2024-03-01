## ExtractIcon

```
[DllImport("shell32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr ExtractIconA(
   IntPtr hInst,
   string lpszExeFileName,
   uint nIconIndex
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extracticona)
