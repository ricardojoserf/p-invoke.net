## ScrollWindowEx

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int ScrollWindowEx(
   IntPtr hWnd,
   int dx,
   int dy,
   ref RECT prcScroll,
   ref RECT prcClip,
   IntPtr hrgnUpdate,
   ref RECT prcUpdate,
   uint flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-scrollwindowex)
