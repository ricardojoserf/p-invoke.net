## BlockInput

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool BlockInput(
   [MarshalAs(UnmanagedType.Bool)] bool fBlockIt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-blockinput)
