## EnumPwrSchemes

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool EnumPwrSchemes(
   IntPtr hUser,
   uint Flags,
   ref IntPtr pRet,
   ref uint lpdwBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-enumpwrschemes)
