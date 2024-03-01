## EnumTimeFormats

```
[DllImport("kernel32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool EnumTimeFormatsA(TimeFmtEnumProc lpTimeFmtEnumProc,
   uint lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumtimeformatsa)
