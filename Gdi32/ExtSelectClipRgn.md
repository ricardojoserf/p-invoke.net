## ExtSelectClipRgn

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int ExtSelectClipRgn(
   IntPtr hdc,
   IntPtr hrgn,
   int fnMode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extselectcliprgn)
