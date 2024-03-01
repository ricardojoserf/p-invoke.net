## GetClassInfoEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetClassInfoExA(IntPtr hinst,
   string lpszClass,
   out WNDCLASSEXA lpwcx
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getclassinfoexa)
