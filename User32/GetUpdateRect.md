## GetUpdateRect

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetUpdateRect(
   IntPtr hWnd,
   out RECT lpRect,
   bool bErase
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getupdaterect)
