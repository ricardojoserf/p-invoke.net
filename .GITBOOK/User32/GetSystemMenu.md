## GetSystemMenu

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr GetSystemMenu(
   IntPtr hWnd,
   bool bRevert
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getsystemmenu)
