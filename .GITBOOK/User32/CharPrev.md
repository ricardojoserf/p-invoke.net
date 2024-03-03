## CharPrev

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr CharPrev(
   [In,
   Out] IntPtr lpszStart,
   IntPtr lpszCurrent
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-charprevw)
