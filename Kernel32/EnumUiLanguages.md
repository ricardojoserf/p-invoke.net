## EnumUiLanguages

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumUILanguages(
   EnumUILanguagesProc lpUILanguageEnumProc,
   uint dwFlags,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumuilanguagesw)
