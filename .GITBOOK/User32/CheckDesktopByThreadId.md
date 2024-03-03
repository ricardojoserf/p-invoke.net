## CheckDesktopByThreadId

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckDesktopByThreadId(
   uint idThread,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszDesktop
);
```

