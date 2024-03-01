## CheckWindowThreadDesktop

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckWindowThreadDesktop(
   uint idThread,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszDesktop
);
```

[Microsoft documentation](TODO)
