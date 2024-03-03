## GetUpdateRgn

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr GetUpdateRgn(
   IntPtr hWnd,
   IntPtr hRgn,
   bool bErase
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getupdatergn)
