## EnumDateFormats

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumDateFormats(
   EnumDateFormatsProc lpDateFmtEnumProc,
   uint Locale,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumdateformatsw)
