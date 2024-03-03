## GetClassInfo

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetClassInfoA(IntPtr hInstance,
   string lpClassName,
   [Out] out WNDCLASS lpWndClass
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getclassinfoa)
