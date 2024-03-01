## WNetEnumResource

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetEnumResource(
   IntPtr hEnum,
   ref uint lpcCount,
   IntPtr lpBuffer,
   ref uint lpBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetenumresourcea)
