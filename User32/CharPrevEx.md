## CharPrevEx

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr CharPrevEx(
   uint codePage,
   IntPtr lpStart,
   IntPtr lpCurrent,
   uint flags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-charprevexa)
