## PaintDesktop

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool PaintDesktop(
   IntPtr hdc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-paintdesktop)
