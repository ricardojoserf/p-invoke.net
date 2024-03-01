## CreateDIBSection

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateDIBSection(
   IntPtr hdc,
   [In] ref BITMAPINFO pbmi,
   uint iUsage,
   out IntPtr ppvBits,
   IntPtr hSection,
   uint dwOffset
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createdibsection)
