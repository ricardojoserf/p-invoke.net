## DrawIconEx

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DrawIconEx(
   IntPtr hdc,
   int xLeft,
   int yTop,
   IntPtr hIcon,
   int cxWidth,
   int cyHeight,
   uint istepIfAniCur,
   IntPtr hbrFlickerFreeDraw,
   uint diFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawiconex)
