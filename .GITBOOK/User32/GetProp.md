## GetProp

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr GetProp(
   IntPtr hWnd,
   string lpString
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getpropa)
