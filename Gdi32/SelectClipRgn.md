## SelectClipRgn

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SelectClipRgn(
   IntPtr hdc,
   IntPtr hrgn
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-selectcliprgn)
