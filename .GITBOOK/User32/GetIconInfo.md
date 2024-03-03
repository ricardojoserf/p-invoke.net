## GetIconInfo

```csharp
[DllImport("user32.dll")]
public static extern bool GetIconInfo(
   IntPtr hIcon,
   out ICONINFO piconinfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-geticoninfo)
