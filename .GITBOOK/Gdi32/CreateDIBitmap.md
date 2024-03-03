## CreateDIBitmap

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateDIBitmap(
   IntPtr hdc,
   [In] ref BITMAPINFOHEADER lpbmih,
   uint fdwInit,
   IntPtr lpbInit,
   [In] ref BITMAPINFO lpbmi,
   uint fuUsage
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createdibitmap)
