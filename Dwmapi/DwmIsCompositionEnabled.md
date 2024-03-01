## DwmIsCompositionEnabled

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmIsCompositionEnabled(
   [MarshalAs(UnmanagedType.Bool)] out bool pfEnabled
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmenablecomposition)
