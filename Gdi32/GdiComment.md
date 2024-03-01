## GdiComment

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GdiComment(
   IntPtr hdc,
   uint cbSize,
   [In] byte[] lpData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gdicomment)
