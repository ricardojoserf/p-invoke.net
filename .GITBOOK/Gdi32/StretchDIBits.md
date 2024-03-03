## StretchDIBits

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int StretchDIBits(
   IntPtr hdc,
   int xDest,
   int yDest,
   int DestWidth,
   int DestHeight,
   int xSrc,
   int ySrc,
   int SrcWidth,
   int SrcHeight,
   IntPtr lpBits,
   [In] ref BITMAPINFO lpbmi,
   uint iUsage,
   uint rop
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-stretchdibits)
