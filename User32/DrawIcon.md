## DrawIcon

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DrawIcon(
   IntPtr hdc,
   int x,
   int y,
   IntPtr hIcon
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawicon)
