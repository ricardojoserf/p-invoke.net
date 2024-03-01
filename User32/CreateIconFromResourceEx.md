## CreateIconFromResourceEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CreateIconFromResourceEx(
   byte[] presbits,
   uint dwResSize,
   [MarshalAs(UnmanagedType.Bool)] bool fIcon,
   uint dwVer,
   int cxDesired,
   int cyDesired,
   uint uFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createiconfromresourceex)
