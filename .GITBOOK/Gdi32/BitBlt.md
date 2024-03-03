## BitBlt

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool BitBlt(
   IntPtr hdcDest,
   int xDest,
   int yDest,
   int width,
   int height,
   IntPtr hdcSrc,
   int xSrc,
   int ySrc,
   uint rop
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-bitblt)
