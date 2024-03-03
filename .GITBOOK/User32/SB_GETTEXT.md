## SB_GETTEXT

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int SB_GETTEXT(
   IntPtr hwnd,
   int iPart,
   StringBuilder pszBuf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/controls/sb-gettext)
