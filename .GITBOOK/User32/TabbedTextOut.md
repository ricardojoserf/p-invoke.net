## TabbedTextOut

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int TabbedTextOut(
   IntPtr hdc,
   int x,
   int y,
   string lpString,
   int chCount,
   int nTabPositions,
   int[] lpnTabStopPositions,
   int nTabOrigin
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-tabbedtextoutw)
