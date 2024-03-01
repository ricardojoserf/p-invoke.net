## MapVirtualKeyEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint MapVirtualKeyEx(
   uint uCode,
   uint uMapType,
   IntPtr dwhkl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-mapvirtualkeyexw)
