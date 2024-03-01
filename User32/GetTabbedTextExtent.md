## GetTabbedTextExtent

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint GetTabbedTextExtent(
   IntPtr hdc,
   string lpString,
   int chCount,
   int nTabPositions,
   [In] int[] lpnTabStopPositions
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-gettabbedtextextent)
