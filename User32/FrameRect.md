## FrameRect

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int FrameRect(
   IntPtr hDC,
   [In] ref RECT lprc,
   IntPtr hbr
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-framerect)
