## EnumSystemLocalesEx

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumSystemLocalesEx(
   EnumLocalesProcEx lpLocaleEnumProc,
   uint dwFlags,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemlocalesex)
