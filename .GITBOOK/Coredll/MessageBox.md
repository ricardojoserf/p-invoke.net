## MessageBox

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int MessageBox(
   IntPtr hWnd,
   string lpText,
   string lpCaption,
   uint uType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-messageboxw)
