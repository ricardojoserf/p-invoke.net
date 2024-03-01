## WNetOpenEnum

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetOpenEnum(
   uint dwScope,
   uint dwType,
   uint dwUsage,
   IntPtr lpNetResource,
   out IntPtr lphEnum
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetopenenuma)
