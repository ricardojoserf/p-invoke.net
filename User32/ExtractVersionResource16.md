## ExtractVersionResource16

```
[DllImport("version.dll", SetLastError = true)]
public static extern IntPtr ExtractVersionResource16(
   string lpszFilename,
   IntPtr lpszLang,
   out VS_FIXEDFILEINFO lpFfi
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-extractversionresource16)
