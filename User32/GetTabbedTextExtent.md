## GetTabbedTextExtent

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint GetTabbedTextExtent(
   IntPtr hdc,
   string lpString,
   int chCount,
   int nTabPositions,
   [In] int[] lpnTabStopPositions
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-gettabbedtextextenta#:~:text=The%20GetTabbedTextExtent%20function%20computes%20the,the%20dimensions%20of%20the%20string.)
