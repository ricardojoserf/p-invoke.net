## GetPixel

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetPixel(
   IntPtr hdc,
   int nXPos,
   int nYPos
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getpixel)
