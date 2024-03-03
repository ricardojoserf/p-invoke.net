## WinHelp

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool WinHelp(
   IntPtr hWndMain,
   string lpszHelp,
   uint uCommand,
   ulong dwData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-winhelpa)
