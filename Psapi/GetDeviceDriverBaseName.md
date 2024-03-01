## GetDeviceDriverBaseName

```
[DllImport("psapi.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint GetDeviceDriverBaseName(
   IntPtr ImageBase,
   StringBuilder lpBaseName,
   uint nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getdevicedriverbasenamea)
