## MessageBoxEx

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int MessageBoxEx(
   IntPtr hWnd,
   string lpText,
   string lpCaption,
   uint uType,
   ushort wLanguageId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-messageboxexw)
