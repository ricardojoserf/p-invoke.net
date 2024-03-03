## EnumSystemLocales

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumSystemLocales(
   EnumLocalesProc lpLocaleEnumProc,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemlocalesw)
