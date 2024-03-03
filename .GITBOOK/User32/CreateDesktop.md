## CreateDesktop

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr CreateDesktop(
   string lpszDesktop,
   IntPtr lpszDevice,
   IntPtr pDevmode,
   uint dwFlags,
   uint dwDesiredAccess,
   IntPtr lpsa
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createdesktopa)
