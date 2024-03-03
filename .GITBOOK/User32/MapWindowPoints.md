## MapWindowPoints

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int MapWindowPoints(
   IntPtr hWndFrom,
   IntPtr hWndTo,
   ref POINT lpPoints,
   uint cPoints
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-mapwindowpoints)
