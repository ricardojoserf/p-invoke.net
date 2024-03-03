## SetPixel

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SetPixel(
   IntPtr hdc,
   int x,
   int y,
   int color
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setpixel)
