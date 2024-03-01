## UnpackDDElParam

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UnpackDDElParam(
   uint msg,
   IntPtr lParam,
   out IntPtr puiLo,
   out IntPtr puiHi
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-unpackddelparam)
