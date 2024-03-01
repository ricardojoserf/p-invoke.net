## LoadImage

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr LoadImage(
   IntPtr hInst,
   IntPtr lpszName,
   uint uType,
   int cxDesired,
   int cyDesired,
   uint fuLoad
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-loadimagew)
